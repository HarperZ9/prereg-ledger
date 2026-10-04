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

## 2026-10-03 (America/Los_Angeles), entry 7

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation. Zain
Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Discernment slice 0, iteration 8 detector pre-registration (blind confirmation) | ae31e87963bcf1651bb990c65caf8fb5516e04a436466ff630d2feeb79ff8242 | file hash of slice0/iter8/PREREG.md; written before overlay8 or sealed8 was listed or opened, before iter8/PLANT.md existed, and before any iteration 8 calibration ran |

Pushed before the result it governs. Note: two entries above carry the heading "entry 6"; this entry
takes the next free number.

## 2026-10-03 (America/Los_Angeles), entry 8

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and the
2026-10-03 approval of the synthesis recommendations. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Flywheel cost-floor decision and bar | 6253144156f15af56288696b616b5f209fb8609c6582a6e277fa8100caaba428 | file hash of project-docs/records/cost-floor/DECISION.md (branch claude/cost-floor); written before the floor was computed on the full hard_v2 log |

Limits: the floor was computed on the 50-call hard-set log as a smoke test after this file was
hashed and before this push.

Correction: this entry was pushed with the heading "entry 9"; it is entry 8. Two entries carry the
heading "entry 6": the effort-gate entry (pushed first, commit 4c53220, renumbered in the next commit)
and the entry after it. Hashes and scopes are unchanged; the push log orders them.

## 2026-10-03 (America/Los_Angeles), entry 9

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and his
2026-10-03 instruction to act on the organizer reply. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| MMBU amendment for the organizer answers of 2026-10-03 (includes DC-19 amendment 1, local scoring pins, judge-change risk) | 09208a9589544347492518ef7294e06821afc4f14f201e6b2e35fc9761573873 | file hash of mission-control/2026-10-02-mmbu/AMENDMENT-ORGANIZER-ANSWERS-2026-10-03.md; written before any scoring module, row renderer or frozen artifact changed |

The answers rest on the organizer's pinned Discord reply as relayed by the author; the brief
(72589a77...) and dev card README at revision 069da7bb (b425ac65...) were fetched and hashed the same
day. The criteria-v1 block hash (3f432ac3...) still verifies; DC-19 is governed by this amendment from
this push forward.

## 2026-10-03 (America/Los_Angeles), entry 10

Signer: Claude Opus 5.5 (an Anthropic model), recording a decision of the lead session made under the
author's 2026-10-02 delegation. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Discernment slice 0, iteration 8 closure | 8e8666185ea5a406278f60c3d7ec630dd1228f8ef08e9da68a1bd83bf721fc15 | file hash of slice0/iter8/CLOSURE.md |

Iteration 8 (pre-registration ae31e879, entry 7) is closed without detection. A safety classifier
stopped its planter, and the planter is not rerun with other encoders, since that would route around
the check. The calibrated fixes carry forward. Iteration 7 stands as the slice 0 result, with this
stated limit: iteration 7 was not blind to plant shapes, so slice 0 recall carries that caveat. A blind
check comes later from defects found naturally in slice 1 by a reviewer who never saw the detector.

Void: D:/datasets/discernment/slice0/sealed8/planter/pngfid.py (2,292 bytes) and ingest8.py
(1,845 bytes), written by the stopped planter. Not opened, not hashed, left in place.

## 2026-10-03 (America/Los_Angeles), entry 11

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and the
lead session's instruction of 2026-10-03. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| MMBU experiment 2 plan (zero-shot Qwen3.5-2B, dev set, official prompts and JSON shells) | 4fed107d11508d2d2a36531e877ff3cce045851e5c8352ed26ae64a91e50a1e2 | file hash of mission-control/2026-10-02-mmbu/exp2/PLAN.md; written before any experiment 2 generation |

Checkpoint-selection evidence only, under organizer answer 6 as recorded in entry 9. Nothing from this
run enters training. The scorer was checked before the run on an oracle reply set built from the dev
key (T_em 3,146 of 3,147; shuffled-key control 18 of 3,147).

## 2026-10-03 (America/Los_Angeles), entry 12

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and the
lead session's instruction of 2026-10-03. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Gather G3 v2 pre-registration (quote required on every citation, regenerate up to 2 times) | 8c14e213becbc31957dc90df5acc4dfe85b0458ab845d1f4ec68ebaf87f94e89 | UTF-8 bytes strictly between the g3v2-prereg start and end marker lines of mission-control/2026-10-03-synthesis/GATHER-DECISION.md, LF line endings, 4,396 bytes; written before any G3 v2 code change or run |

The G3 null (pooled citation precision 19/88 and 23/62, both under a 0.80 Wilson lower bound) stays as
recorded in the same file. G3 v2 holds the question set, models, metric and bar fixed and changes only
the prompt rule and the regenerate step.

## 2026-10-03 (America/Los_Angeles), entry 13

Signer: Claude Opus 5.5 (an Anthropic model), recording the author's approval as given to the MMBU
session in chat, under his 2026-10-02 delegation. Zain Dana Harper did not sign personally.

Approval, the author's words in chat on 2026-10-03: "Downloads approved." It covers the 12 files in
mission-control/2026-10-02-mmbu/slice1/DOWNLOAD-REQUEST.md. The lead session fetched them into
D:/datasets/discernment/slice1/raw/. All 12 sizes equal the expected bytes. The four Zenodo files also
match Zenodo's MD5 checksums; the NLM and Broad hosts publish no checksum, so those eight rest on size
plus the SHA-256 below. The MMBU session recomputed every SHA-256 below from the files on disk before
this push, and each equals the manifest.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Slice 1 download manifest (MANIFEST.tsv) | a9e9c49144d73589809f0c6b26c7ce4fa6baf8d888c1fec090e87cf14e63277c | file bytes of D:/datasets/discernment/slice1/raw/MANIFEST.tsv (file, expected and actual bytes, host MD5 status, SHA-256, URL per file) |
| camelyonpatch_level_2_split_valid_x.h5.gz (PCam, Zenodo 2546921) | f82ee1670d027b4ec388048d9eabc2186b77c009655dae76d624c0ecb053ccb2 | file bytes, 805,965,320 |
| camelyonpatch_level_2_split_valid_y.h5.gz (PCam) | ce1ae30f08feb468447971cfd0472e7becd0ad96d877c64120c72571439ae48c | file bytes, 3,038 |
| camelyonpatch_level_2_split_valid_meta.csv (PCam) | 8ea89aed388b946c2e869db3dc2f3c0816b643247a830a838ce47e74dfbcd82b | file bytes, 1,850,810 |
| NuInsSeg.zip (Zenodo 10518968) | f606aac71112ea0915d55183d0911b5b66f86cabc265b09dbebbd4abb2a15271 | file bytes, 1,627,427,342 |
| NIH-NLM-ThinBloodSmearsPf.zip (NLM) | 3d86af70b3a80d7ecdcc07f8fee0d0d9c9c197cccd907e239abb92c0357c3ea9 | file bytes, 690,355,704 |
| Dataset_statistics.xlsx (NLM) | f4e8abe005763b97c0480c347ec19e016d6138b1f9dec37d2cc8aab53bc7b974 | file bytes, 66,112 |
| images.zip (BBBC039) | 6f30a5d4fe38c928ded972704f085975f8dc0d65d9aa366df00e5a9d449fddd7 | file bytes, 77,915,748 |
| masks.zip (BBBC039) | f9e6043d8ca56344a4886f96a700d804d6ee982f31e2b2cd3194af2a053c2710 | file bytes, 2,753,811 |
| metadata.zip (BBBC039) | a2c1f900bed9ba92a99553efd4c2ae98598433691c7401d818653ab61110deb2 | file bytes, 17,816 |
| BBBC034_v1_dataset.zip | 29c8981502e9f3bc84d0055e0ed6488f0145f712a1cf79389b934c83193cd381 | file bytes, 572,167,675 |
| BBBC034_v1_DatasetGroundTruth.zip | b215c74b9872041ba69c586d84d933d88d0a8b836b4c6da441ca6aac20cc946b | file bytes, 713,766 |
| BBBC032_v1_dataset.zip | 02df5ca7cdc9afb751c63161cabc0e7967310ed1911edaa8572764fb44455321 | file bytes, 1,144,926,586 |

Pushed before any of these archives was opened for the slice 1 build. Invariant I-2 holds: PCam and
the NLM smears are tier Q2, so their rows may serve measurement and a research fine-tune and never a
submission-tagged run.
