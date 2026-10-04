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

## 2026-10-04 (UTC), entry 14

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and the
lead session's 2026-10-03 instruction to freeze F1 before any training. Zain Dana Harper did not sign
personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Freeze F1 (criteria for scale, signed after slice 1) | 7118b76d64bc73d370c37a48cc13813f464cf15ee8a0141db4bbcad10d6a183e | file hash of mission-control/2026-10-02-discernment/F1.md |
| Criteria v1 block, re-derived | 3f432ac39a1da6be10ecc01a1d5b382fc3b31ef061206485b2744ba4585a14db | unchanged since entry 1 |
| Slice 1 full build fact table | 9e4dcd60b2a60339d67ccd419076005b5e74e07fe8e64d85723a989b8f635049 | records plus facts hashes, builds full1 and full2 identical |
| Slice 1 full build rows | 7cdc9ab03135d6d6e99c0c1ec89f983e342417a16d4821e5f3ef025814a315bd | rows.jsonl, 3,346 rows over 1,727 images |

F1 carries criteria v1 unchanged, with no criterion raised or lowered, and lists every slice number
seen before signing. Pushed before any optimizer step. Scope: research fine-tune only (Q2 sources
present, I-2). The blind rationale writer was stopped by an API safety classifier before writing a
line and was not retried, so the first fine-tune trains on program-only targets.

## 2026-10-04 (UTC), entry 15

Signer: Claude Opus 5.5 (an Anthropic model), acting under the author's 2026-10-02 delegation and the
lead session's 2026-10-03 instruction. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| MMBU FT1 pre-registration | e7bb7b736b36a10b28b179bcd7957ba8a1f13bcd5e53ac694f10ec41d04ca873 | file hash of mission-control/2026-10-02-mmbu/train/PREREG.md |
| FT1 training config | 283b631c5b8cf94ed56adb0bf3704e0c3997d3a574c7860b97a5480cd01b732b | file hash of train/ft1_config.json |
| FT1 training rows | de13068959892a449589361057d82ee100acea022b7e963be9b5025f3a55bce3 | train_rows.jsonl, 2,076 rows, program-only targets |
| Held-out-source evaluation rows | 64db95f4a3d990dd5530c29b861da7d88b95dff6509aed51d2fe50caeb2d572c | eval_heldout.jsonl, 800 rows (Kather 2016, BBBC039) |
| In-source evaluation rows | b98b069997ed82c8c1e871f07b8f778e6b70c1ccf51827771332de59f63c1c0a | eval_insource.jsonl, 238 rows |
| Held-out rule output | 788ce8f50874c3085988cb8b52cb3516181c2cd0b5a225e92e4f64083f1166b3 | heldout.json (R-HELDOUT-SRC-v1) |

Pushed after a three-row harness dry run, which saved nothing, and before the first evaluation
generation or optimizer step. Research checkpoint only (Q2 sources in training, I-2).

## 2026-10-04 (UTC), entry 16

Signer: Claude Opus 5.5 (an Anthropic model), under the author's 2026-10-02 delegation. Zain Dana
Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| FT1 results | cbb200ce3a4be9225efb033976e542867913189b004fd505d94aac5cbdeb53e0 | file hash of mission-control/2026-10-02-mmbu/train/RESULTS-FT1.md |
| FT1 LoRA state | c695687530c13b2e58ca15e1a8ac6e4581f4fc4b87bface31c7faf25350055cd | lora_state.pt after 259 steps |
| FT1 dev runs, Pass 1 / Pass 2 | d9b8b88e7c97b3c38abf5e6f617681d30eae6494a13d094ead27ad52481a8bb1 / 7e2e9cd7f86f94dd4cf36370d7362a97784fb529bcdb5d8e2680900fda49979c | exp3/runs/FT1_task.jsonl and FT1_context.jsonl |
| FT1 dev scores | de0b9bb4945c886562141f8e8d3f704856c1017f5656a943c68e223c5b612580 | exp3/exp3_results.json |

These results are governed by entry 15. The pre-registered held-out answer bar was not met (FT1 minus
zero-shot +0.040, cluster 95% 0.000 to 0.079), so the change trigger fires: data work next, no larger
run. Recorded as a null.

## 2026-10-04 (UTC), entry 17

Signer: Claude Opus 5.5 (an Anthropic model), under the author's 2026-10-02 delegation and the lead
session's decisions of 2026-10-04. Zain Dana Harper did not sign personally.

Correction to entries 14 and 16, which stay as written. The author corrected the terms wording on
4 October 2026. The observed fact: an API classifier stopped the blind rationale writer before it wrote
any line, and reported category "reasoning_extraction". The current terms, fetched 2026-10-04T03:37:17Z
and quoted:

- Commercial Terms (effective June 17, 2025), D.4: "Customer may not and must not attempt to (a) access
  the Services to build a competing product or service, including to train competing AI models or resell
  the Services except as expressly approved by Anthropic". Section B: Customer "owns its Outputs."
- Consumer Terms (effective October 8, 2025), section 3 prohibits use "to develop any products or services
  that compete with our Services, including to develop or train any artificial intelligence or machine
  learning algorithms or models". Section 4 assigns Outputs to the user.
- Usage Policy (effective September 15, 2025), "Do Not Abuse our Platform": "Utilization of inputs and
  outputs to train an AI model (e.g., 'model scraping' or 'model distillation') without prior
  authorization from Anthropic".

Any link between the classifier category and a specific clause is inferred. This entry claims nothing
beyond the quoted text. Routes: Claude-free data by default; one licence-checked open-weight writer arm
(pre-registered below); prior authorization from Anthropic, which is the author's outbound call.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Correction record | f60220d3f92fec61ed93e5b4a8101c8b24b632d39a2cd4cd556585fa8c16d9f2 | file hash of mission-control/2026-10-02-mmbu/CORRECTION-2026-10-04-WRITER-TERMS.md |
| Fetched terms and licence pages | 457e95d2748cda36f318356e2413ed37f0e076924dbdfe411779646999dd40b9 | file hash of train/writer_arm/evidence/SHA256SUMS (three anthropic.com/legal pages, the Qwen3-VL-2B-Instruct card, the Qwen3-VL Apache 2.0 LICENSE, the Hub API record) |
| Writer arm pre-registration | e7c0a56689d01343c58a409794d2fe438f441f88cd649ce9a0dc219956c260fa | file hash of mission-control/2026-10-02-mmbu/train/writer_arm/PREREG-WRITER.md |
| Writer model weights (Qwen/Qwen3-VL-2B-Instruct @ 89644892) | 7de1838c87a5349b016c26a1c3f7d2bc400a3d485f95ef39a7059ffd734977a0 | model.safetensors; licence Apache-2.0 |
| Detection row program | a3ef21c110b43fdeaa20ac271c222b79261eac3fd13a001cb740120fbfd61bea | train/detrows.py |
| Detection rows (box answers) | 89cd1446cd2d32b603c2e3f56c338258649326df00bb2a32ad04ee3cedb98894 | det_rows.jsonl, 202 rows: BBBC010 80 multi-box and 78 single-box, NuInsSeg 44 single-box |
| Next training row set | 0564119718cc470f3c1559fb592cfef91aa5b8219f4eb8eaa1a55ccafa8f8354 | train_rows_v2.jsonl, 2,278 rows (FT1's 2,076 plus the 202 detection rows); every rendered target passes DC-19 |

Pushed before the writer model generated any line. Research scope only: the rows hold Q2 sources (I-2).
If the organizers move the judge to a Qwen model, Qwen-written rows wait for their answer before any
submission-tagged run (entry 9 guard).

## 2026-10-04 (UTC), entry 18

Signer: Claude Opus 5.5 (an Anthropic model), under the author's 2026-10-02 delegation and the lead
session's decisions of 2026-10-04. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Writer arm result (null) | eaecc859d2ca0f2362b228c8f99ee6a7bfa43e20859a618b51cbfa3483306ce5 | file hash of mission-control/2026-10-02-mmbu/train/writer_arm/RESULTS-WRITER.md |
| Writer lines (Qwen3-VL-2B-Instruct, Apache-2.0) | 3ef8cab881d4cd5653bf8f275fc0f0b746dd217532214c3c2230befa62ba791f | SHA256SUMS over writer_qwen/outA_*.jsonl and outB_*.jsonl, 2,076 lines |
| Writer program as run (prompt revision 2) | e3e1f5e0ee1a7f4e7382cba9ae0e8ef29d16bafbb5029c350a85f0ab3caa7ae6 | train/writer_arm/writer_local.py |
| Near-duplicate check (DC-3) | 0486744ac434e9de0cf2a2fe00ebfb0df3e80558bc90b5bfb3e0b6b9a694bfbc | file hash of slice1/NEARDUP-CHECK-2026-10-04.md |
| Per-pair verdicts | cd2a7944d69a483d30b107e5f5488437ca989492ae23b50f04fe7345c37a50ba | slice1/neardup_verdicts.jsonl, 131 pairs, 131 distinct |
| Slice 2 download request (not approved, nothing fetched) | 9356347389baa6c1dbbf6402482bc244b2c561e625fff44e3f9f1b5624609344 | file hash of slice2/DOWNLOAD-REQUEST.md |
| Slice 2 licence record | 703aa08e41d134b4245e83ae419d5dd66a641300fd4fabd204502e3ec1f937ca | slice2/sources_licences.json |

Governed by entry 17. The writer arm missed its pre-registered coverage gate: 54 of 1,080 context rows
and 1 of 960 classification rows were accepted, against 20% each. It is not trained, and the default
stays Claude-free. Recorded as a null. All 131 cross-split perceptual-hash pairs of slice 1 were viewed,
and none is a near-duplicate, so DC-3 is met. The download request waits for the author.

## 2026-10-04 (UTC), entry 19

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, under the author's
2026-10-02 delegation ("lead projects and make the calls with written reasons; GPU free; hash signed in
prereg-ledger"). Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Monitorability pre-registration (concept 1 trace-role receipt; concept 2 known-invisible bank, text half) | a0d2b21a5e512b82ac6ce4e360f8faf5d32cc4cfed9ad8295fa71fbfcde49866 | file hash of mission-control/2026-10-04-monitorability/PREREG.md, 15,005 bytes, LF line endings |
| Item banks | c07ef6bff054a43c577224370c3b941b2c361961b3baf48709902b65d441704d; 6a97151bafcef5d148db80e6d043305c2cd834302086b0ec8ddb8b934bf7ec52 | run/items_c1.jsonl (1,200 items); run/items_c2.jsonl (1,000 items) |
| Run and analysis programs | b308684f4ffaeafbc57542f82497a4cb9762221dd8a6004af63a895c4f93f598; dac095f649e412f96c0c35804fba4d79ed6e7ffda21cb230ee537c09b30abf13 | run/run_all.py; run/analyze.py (common.py and gen_items.py hashes are inside the prereg) |
| Subject model weights (qwen3:8b, Ollama 500a1f067a9f) | a3de86cd1c132c822487ededd47a324c50491393e6565cd14bafa40d0b8e686f | GGUF model blob in the local Ollama store |

Written before any model call for this run. No training, no download, no API spend. Not committed or
pushed by the signer; the lead session decides the push.

## 2026-10-04 (UTC), entry 20

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, under the author's
2026-10-02 delegation ("lead projects and make the calls with written reasons; GPU free; hash signed in
prereg-ledger"). Zain Dana Harper did not sign personally. The Qwen3-VL 4B and 8B weights were fetched
under the author's 2026-10-04 approval ("downloads approved").

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Representation series pilot pre-registration (VISTA synthesis section 7, with rescout 4.2 null arms and a monitor arm) | 5f6fc9ca3e832615d83ac0ac368c7ef5a05ba9dc819523698561dc590c18b6c8 | file hash of mission-control/2026-10-04-vista-latent/PREREG.md, 14,267 bytes, LF line endings |
| Game sets G and G-dev | 5f3fb3e7e9b92d48a859555bbdcca6287c54676ef95e12a4b2f17176b4c67100; 9b3cc45b71828cf211b3488cb436f88050f5e2ea173cfab4f88982c455f8a6cc | run/games_G.jsonl (40 games, seeds 704000 to 704039); run/games_Gdev.jsonl (10 games, seeds 709000 to 709009) |
| Generator, arms, runner, series driver | ccbc7756ee60da0f0ccd0b1bceee23e38f3ca14c7d2ac617896770d66bc10ea1; 6b12d6e6b07996900d4b8d6ff63eec7eaa5c072734722a41e1c3f18d5d55bbfc; 31ea0ea5b4419e7a0206174529a3e3e3b86b8459cf8cc15b4b9ff30613e1c64a; 7a72c17101d60c8ce5291aeb17e78e934190bb8d5838570962c4dd63e91d98ba | run/games.py; run/arms.py; run/run_model.py; run/run_series.sh |
| Decision rule, monitor, analysis, parity check | a6aafe218e3d24800caef341260782bfb401c1cdd467044d22f9c558e8df0573; 3909b067ee93ef31a65a81fa07a9aede27a44857035331ef01fde5e0fa5d1818; 4e44938695bf75299cc41c0e26487b70170c336e4d2607ac8b3361bd8d747e9b; b28cda11cd01a523db0ab8f23b5bcb544ecabf61ae73b93f429ac974e046db98 | run/decide.py; run/monitor.py; run/analyze.py; run/check_parity.py |
| Subject model weights (Qwen3-VL-4B-Instruct @ ebb281ec, Qwen3-VL-8B-Instruct @ 0c351dd0; Apache-2.0) | bbf722d0eb2e46d0db90861383e19bb1bde179f4313589020c945d1fbfd5245f | file hash of run/weights_sha256.txt (sha256 of all six safetensors shards); Qwen3-VL-2B-Instruct @ 89644892 weights as in entry 17 |

Written before any model call for this series. Scripted controls only (no model) ran before hashing: the
optimal harness check completed 120 of 120 levels in all 8 arms, and the seeded random floor was 16 to 24
of 120. No training, no new download, no API spend. Not committed or pushed by the signer; the lead
session decides the push.

## 2026-10-04 (UTC), entry 21

Signer: Claude Opus 5.5 (an Anthropic model), the MMBU lead session, under the author's 2026-10-02 delegation
("lead projects and make the calls with written reasons; GPU free; hash signed in prereg-ledger"). Zain Dana Harper
did not sign personally. Slice 2 downloads were approved by the author (core, DSAD, IXI; LUNA16 excluded).

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| FT2 pre-registration | cdb7142671f00a454ecaaa09faddbbad2777fbeabf8a4822ced7f12625c3b1a5 | file hash of mission-control/2026-10-02-mmbu/train/ft2/PREREG-FT2.md, 10,161 bytes, LF |
| FT2 training rows | b7945fb832ad098bc94be0c8256a1f331107f2062a29839160f8dc3fbc2145de | slice2/train2/train_rows_ft2.jsonl, 11,172 rows |
| FT2 held-out rows | 71d260d60b9d3896127bbab2b0fb0f7a9af328ce7a7ed574a69350c6a6a9e796 | slice2/train2/eval_heldout2.jsonl, 2,299 rows |
| FT2 in-source rows | b115e613c4540d3dbeb369baf353a5b80359b371233eb1746f9378cf03b54005 | slice2/train2/eval_insource2.jsonl, 1,080 rows |
| Held-out source draw (R-HELDOUT-SRC-v2) | b3d1f800576f263ab2dbd7201cde3bd875ec87e91cf498465147c87d12352dfb | slice2/train2/heldout2.json |
| Config, pipeline, lock helper | 2169301f16ffad28afe7166e0f2a85e63c45e14e2a92a4d7f2e5cb42e929472e; 91535676f10ae9932cc339ad1a4c4c8c4f16b8886b976f7cbb2ceed94ad3c723; e697a92e57318edbb72d52a2e78264e9a4facdc072cb8ed832e8186bedac3673 | train/ft2/ft2_config.json; train/ft2/run_ft2.sh; train/ft2/gpu_lock_ft2.sh |
| Programs | 4e230b2f8fe86fb331957c0f13d84561f1f8f53c9966a1ff5e566a5a21c78348; 60e3a7728a128e1ce26f34d6fee5cbd8753fb690e451e29f62e725b8f2148f10; 946083d657b7e4c7e435d45da964da5786d6c8d00945784070a832c03f0878e4; 94c415604cefaeca68aa10a5420388920342a1d48fe8be0cab68d3bb68e8d6c4; 2354187af1e4ba6c0d546f1efb4f80e3178b62e45d42470d925481104cef970f | train/train2.py; train/evaluate3.py; train/trainset2.py; train/heldout2.py; train/ft2/score_ft2.py |
| Slice 2 build run1 output hashes | 23cc2358f5de9b03cd0d69d25c313a2edda156e18c966b791bfe972cf8528cb5 | slice2/build/run1/hashes.json (fact table 089862b4..., rows 29968d64...) |
| Slice 2 near-duplicate second stage | b199670bd3980dbe7c6a01c26044684b4ca27bf9602ad2676ae5557e78738cbf | slice2/build/run1/neardup_confirm.jsonl, 17,797 candidate pairs |
| Slice 2 raw integrity | 902dbbcc3fb5adcf6cfde30e57f5c89f4d252e24a97eeea8d8b17a1bad0205f0; f8c4789882b10654b5760537a4a82720a47a6e8342e91f2824ea911d9267db20 | slice2/verify/rehash.jsonl (703 of 703 SHA-256 equal MANIFEST.tsv 68878413...); verify/hostcheck.json (480 host checksums match, 0 mismatch, 223 files without a host hash) |
| Live terms read 2026-10-04T07:42:29Z | f75d4085e6cb0783b00d996b357950a758efb81b9246d0501273c09cd1ebc36e | train/ft2/evidence/SHA256SUMS (Commercial Terms, Consumer Terms, Usage Policy page bytes) |
| Row pre-check | 5169b3c175bf35af43145fdc0deade1f3198a9f20aa9b80793a0d21cc8748e9b | train/ft2/tokcheck.json: 11,172 rows encode within 2,048 tokens; 11,172 rendered replies strict |

Written before any FT2 generation or optimizer step. FT2 targets contain no Claude-written text. Not pushed by
the signer; the lead decides the push.

## 2026-10-04 (UTC), entry 22

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, under the author's 2026-10-02
delegation ("lead projects and make the calls with written reasons; GPU free; hash signed in prereg-ledger").
Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| SEALED-SHARE-1 pre-registration (social-learning synthesis section 6) | 9fa88444a48a7b030c5c4f60b8567a7a578bb3d8aa130dae5b6f05a8b07dcc2e | file hash of mission-control/2026-10-04-social-learning/run/PREREG.md, 13,790 bytes, LF line endings |
| Corpus and answer-key manifests | c60b6e7087efd140e1eecea605be8287bc096ceffd22fe19ab0285c4727028e6; 4b21ff4a31611786362f9fca06b0066d4101528822a74ba7b3109a2a4ac3459c | run/corpus_manifest.sha256 (420 files, seeds 61001 to 61012 and smoke 69001, 69002); run/keys_manifest.sha256 (14 keys) |
| Programs | 578b3bb455d968e8a3885967fdb849adcf4309dde5adbe11c9aae3d6d5704bd2; ec6f129606a5120a37da9501bf33a7557d743c5238c2119dfda8b9e63b287c1a; 63ac17cfe16b4084e18f6109be8f1718b0384182425d3df51eceac93ba39ae44; 9ffd73a38f6b7ad45c8edcb402d5c1b0b5bc178edd437237a13fcc6b250cbf08; 6e6bcbb0e8152a27ec3b22c6b81e580fdeb62ccde7362a3d36ef2dbac3a55b0a | run/gen_corpus.py; run/runner.py; run/analyze.py; run/baselines.py; run/series.sh |
| Subject model weights (qwen3:8b, Ollama 500a1f067a9f; olmo2:7b, Ollama 4208d3b406db) | a3de86cd1c132c822487ededd47a324c50491393e6565cd14bafa40d0b8e686f; ea89e3927d5ef671159a1359a22cdd418856c4baa2098e665f1c6eed59973968 | GGUF model blobs in the local Ollama store, rehashed 2026-10-04 |

Written before any model call for this run. Scripted controls only (no model) ran before hashing: the oracle
recovered 5 of 5 high-value sentinels on all 12 seeds; the random opener averaged 4.75 of 5. No training, no
download, no API spend. Not committed or pushed by the signer; the lead session decides the push.

## 2026-10-04 (UTC), entry 23

Planted-null canary on agent reports.

Signer: Claude Opus 5.5 (an Anthropic model), the lead session, on the author's chat instruction of 2026-10-04
("run the planted-null test now"). Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration | fd14b1153f6cdd2be5efcbefd12cd943c634bb31c774a1558136c09a87adbf82 | file hash of mission-control/2026-10-04-planted-null/PREREG.md (includes the PLANTS.json hash) |

Written before any report agent was launched. Not committed or pushed by the signer.

## 2026-10-04 (UTC), entry 24

Planted-null canary, no-tell rerun.

Signer: Claude Opus 5.5 (an Anthropic model), the lead session, on the author's chat instruction of 2026-10-04
("run the no-tell rerun"). Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration | c8cfcf2dd2f3962ee0a359e940e7342e2d5f01b098f97c307512eddae66d6f39 | file hash of mission-control/2026-10-04-planted-null/rerun/PREREG.md (includes PLANTS.json and KEY.json hashes) |

Written before any report agent was launched. Not committed or pushed by the signer.

## 2026-10-04 (UTC), entry 25

Local Jev-class judge: Clef-flash latency floor on the F1 rows and the Canny head-to-head on the claims-v1 test split.

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, on the author's chat instruction of
2026-10-04 relayed by the lead ("Run the preregistered Canny head-to-head plan ... Write and hash the prereg first").
Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration | 14cc279beef9fcde1f9612976cd72d715d46be72390103b91266bf46da7bd035 | file hash of mission-control/2026-10-04-jev/h2h/PREREG.md, 6,932 bytes, LF line endings |
| Question texts | f8ee0d216ce1ec3c9dafe9cdcb5dead226719b16f51a744f5af36627a5d5badf | h2h/questions.json |
| Server and lock programs | bc0d739266c8a12585ee94665e1c4f28bbf20c2cc1de29d71b543ab0d05bdf1d; 716c045d494cdecd300dabf19992158ee7ba44cb8dc1fd4074089d8ca7218ff4 | local-judge/serve_clef.py; local-judge/gpu_lock.py |
| Test split | 5282f9211b82d45ec10c8bee9f9d00516a82501df5950cd6fc28f8fc23dea93e | D:/classifiers/claims/data/b_test.jsonl, unread by any Clef or Canny arm |

Written before any Clef-flash call on claims data and before the test file's contents were read. The J2 combiner,
thresholds and scoring programs follow as a separate entry before any test row is read. Measures Clef-flash, not Jev.
Not committed or pushed by the signer.

## 2026-10-04 (UTC), entry 22

Signer: Claude Opus 5.5, the MMBU lead session, under the same delegation. Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| GPU lock helper for FT2, revision 2 | d2fe56a15690e99b08dad7b4eacd1728950f7621f134b2ed00539e3277dd97fc | train/ft2/gpu_lock_ft2.sh (replaces e697a92e... of entry 21) |

Amends entry 21 before any FT2 GPU step; no other file, bar or row changes. Two lock defects, raised by the
coordinator, are fixed: (D-1) the FT1 abort at 01:36Z released a lock while the stopped owner's child python still
held the GPU, so a second acquirer started beside it; release now refuses until every recorded step pid is dead,
and each step re-checks ownership. (D-2) the waiter printed an empty holder for a JSON OWNER file; it now reads both
formats and reports whether the holder's pids are alive. It never breaks another owner's lock. The first FT2 waiter
(which held no lock) was stopped by PID and relaunched with revision 2.
