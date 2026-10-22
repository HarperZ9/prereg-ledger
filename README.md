# prereg-ledger

A public list of SHA-256 fingerprints for study plans, written down before the results they govern. Each entry in `ATTESTATIONS.md` names a preregistration, gives its hash, and says exactly which bytes the hash covers. Anyone holding the original file can hash it and compare. Anyone can check when an entry first appeared on GitHub.

The ledger records Zain Dana Harper's own experiments: the MMBU biomedical question-answering work, the discernment and Telos studies, and Flywheel evaluation settings. It holds 92 entries from 2 to 16 October 2026. The format is plain Markdown in a git repository, so you can copy it to start a ledger of your own.

## What an entry looks like

Each entry has a date heading, a signer line, and a table:

| Record | SHA-256 | Scope of the hash |
| :-- | :-- | :-- |
| Name of the plan or amendment | 64 hex characters | Which file or byte range was hashed, and when it was written relative to the result |

A limits paragraph follows when the timing needs explaining. Some plans were written before their results but reached the ledger after them, and those entries say so.

## Check an entry

The ledger stores hashes only. To check one you need the original file, which stays with its author. Hash it and compare the result with the table:

```
sha256sum PREREG.md
```

To find the commit that first added a hash:

```
git clone https://github.com/HarperZ9/prereg-ledger
cd prereg-ledger
git log -S 3f432ac39a1da6be10ecc01a1d5b382fc3b31ef061206485b2744ba4585a14db --reverse --format='%h %ad %s' --date=iso -- ATTESTATIONS.md
```

The first line of output is the commit that introduced it. Commit dates are set by whoever made the commit, so they are not independent evidence. GitHub records its own push times, which the repository owner cannot edit:

```
gh api "repos/HarperZ9/prereg-ledger/activity?per_page=100" --jq '.[] | "\(.timestamp) \(.after[0:7])"'
```

Each line is a push and the commit it ended on, newest first. An entry was public no later than the first push at or after its commit. On 22 October 2026 this list reached back to the first push, on 3 October 2026 UTC.

## Limits

- The repository owner can rewrite git history. The GitHub push log is the outside timestamp.
- Hashes, scopes and limits are never edited after a push. Two entry headings were renumbered in place on 3 October 2026 (commits e62c401 and ed35e1e), and each carries a correction note. Entry numbers 6, 22 and 23 still repeat; entries 8 and 27 explain the duplicates. Other corrections are new entries that name the one they correct.
- Entries 28 to 89 were written between 4 and 16 October 2026 and first pushed on 18 October 2026, so their outside timestamp starts on that date.
- Local file paths in the entries are kept as written, since entries are not rewritten. They point to files on the author's machine and are not fetchable.
- A matching hash shows the file has not changed since the entry was pushed. It does not show the plan was followed, or that it was written before the experiment ran.

## How it compares

[OSF Registries](https://osf.io/registries) and [AsPredicted](https://aspredicted.org) hold the full plan, freeze it, and act as a third-party timestamp. Use them when a journal or reviewer expects a registered report. [OpenTimestamps](https://opentimestamps.org) anchors a hash in the Bitcoin blockchain, which gives a stronger timestamp than a GitHub push log, with no human-readable context. [Zenodo](https://zenodo.org) gives a DOI and a frozen copy.

prereg-ledger keeps only hashes and a plain-language scope for each one, in a git repository you control. It costs nothing, takes a commit per entry, and can record many small amendments in a day. It is weaker evidence than OSF or OpenTimestamps because the timestamp rests on GitHub's push log. Nothing stops you from pairing it with one of them.

## Licence

Apache License 2.0. See [LICENSE](LICENSE).
