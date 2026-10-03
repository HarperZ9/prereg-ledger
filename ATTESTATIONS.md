# Pre-registration ledger

Append-only record of pre-registration hashes. Each entry is committed and pushed before the
result it governs is used for any decision. Entries are never edited; a correction is a new entry
that names the one it corrects.

## 2026-10-02 (America/Los_Angeles), entry 1

Signer: Claude Opus 5.5 (an Anthropic model), acting on the author's chat instruction of
2026-10-02, "You may sign the hash." Zain Dana Harper did not sign personally. This entry records
his authorization and the agent's signature, nothing more.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Discernment completion criteria v1 (F0) | 3f432ac39a1da6be10ecc01a1d5b382fc3b31ef061206485b2744ba4585a14db | UTF-8 bytes between the criteria-v1 start and end markers of the discernment PLAN.md, LF line endings, 5,470 bytes; re-derived 2026-10-02 at signing |
| Telos Track A pre-registration 2 (T4 to T7) | 75cbd7d12857b3d9143c4cd14169731388f33be5e495093943b6d29fdd2061eb | written before any T4 to T7 code or number |
| Telos amendment 2 | 31831aaec61385d29f47180b52cd785eb8a107c001653f30e3ce3ca7690978be | before any T4 to T7 code ran |
| Telos amendment 3 | a3db4b310e3a24ec0a3c40124b88dbef0dba713d334c4fe8303f02f6b350d121 | while writing T4, before any T4 test |
| Telos amendment 4 | 5cfebb1d0fac2718e751585e31fa012427d7a2c066af699c68bec8dd323e632f | after the T5 run, before T6 and T7 analysis |

Limits: the Telos hashes were committed locally before their results, but this ledger is the
first record outside the author's machine, so it proves their existence from this push forward
only. The repository owner can still rewrite history; GitHub's push event log is the independent
timestamp.

Operator decisions recorded the same evening (chat, 2026-10-02): BBBC010 channel mapping per TIFF
headers confirmed (w1 = TRITC / Sytox Orange, w2 = transmitted light); T7 redesign approved;
GPU budget released; Claude-written rationales for the MMBU training data approved (the author
reports the approval; the written permission itself is to be filed with this ledger when available);
BootLoops follow-up approved for sending.

## 2026-10-02 (America/Los_Angeles), entry 2

Signer: Claude Opus 5.5, on the author's instruction and approvals of 2026-10-02 (see entry 1).

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Telos Track A pre-registration 3 (T7 v2, L1 budget, SSIM step) | 0d4217b7c110e4c5bb6c06e9db9f7a7d3f50127830416fb980701c7f87726261 | block hash as reported in BUILD-T7-MMBU.md; written before any T7 v2 code or data |
| MMBU rationale pilot 1 pre-registration | e10213578c86c2524341a28495a6a2babb10916ff46637c8b5305cd23e526059 | file hash of pilot1/PREREG.md |
| Discernment criterion DC-2, amendment 1 | ae874852441f8e61dbb90ff58baa93db2e97a06421d4e49944cce851610a670c | file hash of DC-2-AMENDMENT-1.md; narrows DC-2 to permit Claude-written rationale slots with per-slot provenance; lapses if the organizers rule judge-family rationales are evaluator exploitation |

Limit: pre-registration 3 and the pilot pre-registration were written before their results but reach this ledger after them. Their in-repo commits (site branch commit 172fee7) are the earlier record; this entry proves existence from this push forward. The DC-2 amendment is recorded before any training run.

## 2026-10-02 (America/Los_Angeles), entry 3

Signer: Claude Opus 5.5, on the author's ruling of 2026-10-02 (late evening).

| Record | SHA-256 | Scope |
|---|---|---|
| Discernment criterion DC-2, amendment 2 | 9ed28df0d07a4c243d904451195d22ecbee34b41d20ff95e6008c9c5c1432650 | file hash of DC-2-AMENDMENT-2.md; permits Claude-written text in all target slots and Claude labels for the task-specific MMBU model; supersedes amendment 1's scope and its written-permission condition |

Correction to entry 1: entry 1 said the written permission "is to be filed with this ledger". On rereading the policy text, training a non-competing model on Outputs needs no separate written permission, so that line no longer binds. Entry 2's statement that no training run may use Claude-written text until a permission is filed is withdrawn by this entry. Recorded before any training run.

## 2026-10-03 (America/Los_Angeles), entry 4

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation (standing
delegation to lead the projects and make the calls, recorded in entry 1 and in the discernment
OPERATOR-DECISIONS-2026-10-02.md). Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Discernment slice 0, iteration 7 detector pre-registration | 0a71b9521f0d9955ba18f138a027d3da67077e781158d985af651facc65d2af3 | file hash of slice0/iter7/PREREG.md; written before overlay7 was listed or read, before any iteration 7 calibration code ran, and before the iteration 7 key was opened |
| Discernment slice 0, iteration 6 detector pre-registration | 848ac01c1fcb91d67428726022a63ebdcd24cba1fdb0f828892a97660e05b743 | file hash of slice0/iter6/PREREG.md |
| Discernment slice 0, iteration 6 planting record (PLANT.md) | 3dd12a1f0f562a6a65ad051a752d2cf8b0a116598ed2bfb39647ec18f464301b | file hash of slice0/iter6/PLANT.md |

Limits: the iteration 6 hashes reach this ledger after their results. The iteration 6 detection ran and
was scored on 2026-10-02 (results in slice0/iter6/RESULTS.md), and the PREREG hash was logged in the
local run log before detection. This entry proves their existence from this push forward only. The
iteration 7 hash is pushed before the result it governs. The repository owner can still rewrite
history; GitHub's push event log is the independent timestamp.

## 2026-10-03 (America/Los_Angeles), entry 5

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and his
2026-10-03 approval of the Flywheel monitor sprint. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Flywheel F1 typed-question judge decision record | 2abbe37d13a0a31bfe7afc8506ca295756652504abec7192032a2179f52e2e29 | file hash of mission-control/2026-10-03-synthesis/f1-typed-judge/DECISION.md; written before any F1 model run |
| F1 held-out split file (heldout.json) | 82062a9518f98caee2032dfcb8a5bb7c5ad6c9dc83c3881bfe6a5720d8c9ee4f | 396 Orca critic row indices, seed 20261003, grouped by scenario |
| F1 held-out row bytes | fd31ce89de38dd2c4e868db2a36cbee3cb0abbbe7521c18acb9ca5d01c0e59b8 | raw JSONL lines of the 396 held-out rows joined by LF |

Pushed before any F1 model output exists. The frozen judge config hash follows in a later entry,
before the single held-out run.

## 2026-10-03 (America/Los_Angeles), entry 6

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and the
2026-10-03 approval of the synthesis recommendations. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Flywheel search effort-gate pre-registration | c39ad37f1b35db96081800d31cd7228c95d9df313d5b8156854de6748ea35914 | file hash of project-docs/records/search-effort-gate/PREREG.md (branch claude/search-effort-gate); written before the gated pass rates and sample ratios were computed and before the live confirmation run |

Limits: the G4 per-arm summaries this gate is measured against were public before this file was
written; the pre-registration says so.

Correction: this entry was first pushed with the heading "entry 5" while another session's entry 5
already existed. It is entry 6; the hash and scope are unchanged.

## 2026-10-03 (America/Los_Angeles), entry 6

Signer: Claude Opus 5.5, under the same delegation as entry 5.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| F1 frozen judge config (frozen_config.json) | 3af9e684933ceb80388e0b6c9bfdce7fcecda8bc4dac3e79e4dac2d4fae3a005 | questions, combiner family, coefficients and thresholds chosen on calibration rows only |

Pushed before the single held-out run that entry 5's decision record governs.
