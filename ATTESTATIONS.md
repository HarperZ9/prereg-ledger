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

## 2026-10-04 (UTC), entry 26

Replay receipt prototype for continual learners (Sutton-lineage synthesis, key finding 2), CPU only.

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, on the lead session's instruction
("Preregister bars in PREREG.md before running, with the hash appended to D:/prereg-ledger/ATTESTATIONS.md as the
next entry"). The operator's own words were not relayed to the signer. Zain Dana Harper did not sign personally.
Numbered 26 because the highest entry above is 25; the later block headed "entry 22" is an amendment by another
session and was left as written.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration | c8856d4359e859954808374834de0799858f1072e7a2950873d683f8673bac73 | file hash of mission-control/2026-10-04-sutton-lineage/replay-receipt/PREREG.md, 5,776 bytes, LF line endings (lists the five program hashes) |
| Source code ported | a6b79580d85f3025bdb601566d3627c5f489f13b | git commit of github.com/shibhansh/loss-of-plasticity (MIT), cloned to C:/dev/.scratch/replay-receipt |

Written before any run at the registered seed 20261004. Smoke runs at seed 999 (300 and 600 steps) only checked
that the code executes. No GPU, no training beyond the 10,000-step CPU learner, no API spend. Not committed or
pushed by the signer.

## 2026-10-04 (UTC), entry 23

Signer: Claude Opus 5.5, the MMBU lead session, under the same delegation, acting on the author's chat instruction of
2026-10-04 as relayed verbatim by the coordinator ("then utilize the outputs to build a deterministic tool to place
the labels ~ simply expand the deterministic tool to fill in where this friction point occurs. do this for any
instance where it occurs."). Zain Dana Harper did not sign personally.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| FT2 amendment 1 | cb3fa75b1ae706995e4e73c797a8c5dcbf60d638be53600f7954984343ef28dd | train/ft2/PREREG-FT2-AMENDMENT-1.md |
| Deterministic field generator | d57e0d8db8004ca9edfce3c6ccd9230794e5a3cf2b253e538f03431202db9ed4 | train/fieldgen.py |
| FT2 training rows, generator-filled | 3546373c880750cb127988525e7724ff13ceb5a28508cf63fd41a2bfded9b85e | slice2/train2/train_rows_ft2g.jsonl, 11,172 rows (replaces b7945fb8... of entry 21) |
| Config and lock helper revision 3 | 7795d925f9467a9a435b5d5e0a64fd9e2ad93b54deca34bf34e299ffbe094e14; 6f9f995d4155507e42ddab13bf3ba74d7490317e440d60cf63b9b1542ba35064 | train/ft2/ft2_config.json; train/ft2/gpu_lock_ft2.sh |
| Row pre-check on the new rows | 5169b3c175bf35af43145fdc0deade1f3198a9f20aa9b80793a0d21cc8748e9b | train/ft2/tokcheck.json (11,172 rows within 2,048 tokens; all rendered replies strict; log tokcheck2.log) |

Written before any FT2 GPU step. Bars, arms, evaluation rows and held-out sources are unchanged. The generator
fills slots from source data only and marks the rest UNSOURCED; the Claude writer stopped by the API classifier is
not retried, reworded or rerouted. Two generator runs were byte-identical. Not pushed by the signer.

## 2026-10-04 (UTC), entry 27

Correction by the MMBU lead session (Claude Opus 5.5). I numbered two MMBU blocks without reading past the end of my
own entry 21, while other sessions had already appended entries 22 to 26 uncommitted. Two MMBU blocks therefore
carry duplicate numbers. They are left as written (append-only) and are referenced from now on as:
- "entry 22 (MMBU lock helper)" = MMBU-22, the block whose first table row is gpu_lock_ft2.sh d2fe56a1...;
- "entry 23 (MMBU field generator)" = MMBU-23, the block whose first table row is PREREG-FT2-AMENDMENT-1.md cb3fa75b....
My local commits 40536d2, 9dd661b and efc66e3 also included other sessions' uncommitted entries 19, 20, 22 to 26
(text unchanged). Nothing was pushed. Future MMBU entries take the next free number after reading the whole file.

## 2026-10-04 (UTC), entry 28

fast_judge: a local SystemOne-compatible judge API over Clef-flash, ablated one speed lever at a time.

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, on the author's chat instruction of
2026-10-04 relayed by the lead ("perhaps we could build the competitive API that beats both when paired with the
local model"). Zain Dana Harper did not sign personally. Numbered 28 after reading the whole file (highest so far 27).

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration | a84ccecd0fec0f7d3c43b543723670284f63920b7ed9f508adb4193ef365c5fa | file hash of mission-control/2026-10-04-jev/local-judge/API_PREREG.md, 4,623 bytes, LF line endings |
| Programs | d5f74d5876b36089d042111330537582f032c937809ed1d8df6b2539519ff2b5; 1a62f454abd93fb7c72f73deabe2dbe03047e474f9f16d09d4315403f24c664e; 01ad01894ede3a00844b37073779ba7921a0760fb107b5919f98a391726a8c84 | local-judge/fast_judge.py; local-judge/bench_api.py; local-judge/run_all.py |
| Model digest (served in every receipt) | 0c03d33588d14ceebba0c87b128e4eceb57e723323934592365299956e6de0cc | sha256 over file names and LFS blob ids of Cloudflare/clef-flash snapshot 17f0b0ad |

Written before fast_judge served any request. Same 396 F1 held-out rows and frozen config as entry 25 part A.
Not committed or pushed by the signer.

## 2026-10-04 (UTC), entry 29

Signer: Claude Opus 5.5, the MMBU lead session, under the author's 2026-10-02 delegation and the coordinator's
instruction to adopt feature amendment 2 if FT2 had not taken a GPU step (it had not). Zain Dana Harper did not sign
personally. Numbered 29 after reading the whole file (last entry 28).

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| FT2 amendment 2 (features) | f3b4feaa1cc411bebd6efedba8d3c94c019a44e9aae65fc0c8a258fec7790979 | features/AMENDMENT-FT2-2-FEATURES.md (its own table hashes the feature files, api.py, fx_text.py, validation.json, coverage.json) |
| Lead adoption record | 8a9af9c2184277dcb6ca88401db114eeaf24dc1e1ae698874d66cc4e1f1f0405 | train/ft2/PREREG-FT2-AMENDMENT-2-LEAD.md |
| Rationale lines | cd0a71d31ec57b12a2afb2acb5b1f6a97c9f0dccf19e525fa2a20e11f7da611f | features/out/rationale_ft2g_1.jsonl (re-run by the lead, byte-identical) |
| Generator | d7cdc47031c9d7dccf0d9cfeafcd15270bcf0ce428f4602c28e9d5752e2487ba | train/fieldgen2.py (calls fieldgen.py d57e0d8d...) |
| FT2 training rows (final) | 533101d1ffa5ac007f10e41ccaf63ffb9fb4dcfe58ed011acabbe8af05c1bdd9 | slice2/train2/train_rows_ft2f.jsonl, 11,172 rows (replaces 3546373c... of MMBU-23) |
| Config; pre-check | a4c7e41e67776cf6914f12bab4fc3ec3f685e999fa45c5e486bfc35f39c525e8; 8ea41df475f3cdd6393b60c1860045d0bac0ce239097415b487d57261f5500a1 | train/ft2/ft2_config.json; train/ft2/tokcheck.json (11,172 rows within 2,048 tokens, all strict) |
| Closure decisions | eb60099e205a4f270a2e41df7b7c049da9df8415d4fbf695974ea1c0c39fe9af | features/COVERAGE.md (no closure enters FT2) |

Written before any FT2 GPU step. Not committed by the signer: the working file also holds other sessions'
uncommitted entries, so the lead decides the commit and the push.

## 2026-10-04 (UTC), entry 30

Decoy grading-file arm (eval-realism tell audit).

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, on the author's chat approval of
2026-10-04 relayed verbatim by the lead ("3. yes.", answering "Should I build the eval-tell checklist and the
decoy-rubric test arm next?"). Zain Dana Harper did not sign personally. Numbered 30 after reading the whole file
(last entry 29).

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration, body | c052d419ef6662a9f66f2abae33ffcb15a5a2e0407a956e631a2969b3c271019 | bytes of mission-control/2026-10-04-eval-tells/PREREG.md before its footer marker line, LF (includes the sealed key, setup, decoy-text, scorer and audit hashes) |
| Pre-registration, file | e613c37d8872cf8efb3386b3e53d3505f2a8051cf28f24de29d522adfbf9a5b9 | whole file with footer, 6,884 bytes, LF |

Written before any subject was launched. Not committed or pushed by the signer: the working file also holds other
sessions' uncommitted entries.

## 2026-10-04 (UTC), entry 31

Decoy grading-file arm, repeat 1 (no folder clause, cwd C:/dev, grade-stated arms added).

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, on the author's chat approvals of
2026-10-04 relayed verbatim by the lead ("3. yes." and "You no longer need to wait on my approval. Approved.").
Zain Dana Harper did not sign personally. Numbered 31 after reading the file tail (last entry 30).

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Pre-registration, body | 4f9e8dbcc84680c6ccdaa1ce535a64f12f710391d8ec6014f6132acff2e7505f | bytes of mission-control/2026-10-04-eval-tells/repeat-1/PREREG.md before its footer marker line, LF (includes the sealed key, setup, decoy-text, audit and scorer hashes) |
| Pre-registration, file | 4bf211afe0633749068350479233d295f5cae34932ca1e01a20db741f7959f7f | whole file with footer, 9,765 bytes, LF |

Written before any subject was launched. Not committed or pushed by the signer: the working file also holds other
sessions' uncommitted entries.

## 2026-10-04 (UTC), entry 32

Signer: Claude Opus 5.5, the MMBU lead session, on the lead's decisions under the author's standing grant of
2026-10-04 ("You no longer need to wait on my approval. Approved."), relayed by the coordinator. Zain Dana Harper did
not sign personally. Numbered 32 after reading the whole file (last entry 31). Written before any PS-1 or IR-0 run.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| PS-1 Stage 0 pre-registration | e1cf3f01d681d6ecd58daee0fadc4093a9a9a33dffe2964d050a0ffb7e868ac8 | mission-control/2026-10-02-mmbu/train/ps1/PREREG-PS1.md |
| PS-1 sampler (paper's MH acceptance, not the released hill-climb); gate code | be02f640141fd0fef27c2f42b458b1f5c7a045a4495b2b58498b436932703ae8; 6b3a1c8b946b8ddddccc434ccf1004e363c92a503615f64578ff2776a429abe9 | train/ps1/ps1.py; train/ps1/ps1_gates.py |
| IR-0 pre-registration | f480d7a11d186d592f27dc48916ce9f6d3520a2d03b03ea4d0c0f6002c03e2d4 | train/ir0/PREREG-IR0.md |
| IR-0 runner and scorer | 0323b52ae46b0709accd87bc572468f51f0bb70fc895a33ad17a6807940fc204; 26688c823b084840fa415d0a172fcd315b77174f65b096b259e735f413ccb496 | train/ir0/ir0.py; train/ir0/ir0_score.py |
| Queue (after FT2, behind earlier waiters) | c207c3fe4b12d3a94dd3c09c49c4ae3cd9aed087fd573fabfebb4e7a45bb532c | train/queue_ps1_ir0.sh |

PS-1 gates: G1 at least 20% of 300 rows constraint-preserving; G2 likelihood rise on at least 90% of accepted rows;
G3 100% strict shell. IR-0 stop rule: close for 2B unless the paired 95% interval of insight retry minus
independent resample sits above 0. Neither study preempts FT2. Not committed by the signer (other sessions' entries
are uncommitted in the working file); the lead decides the commit.

## 2026-10-04 (UTC), entry 23

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session. Status line for entry 22: SEALED-SHARE-1 (PREREG.md 9fa88444a48a7b030c5c4f60b8567a7a578bb3d8aa130dae5b6f05a8b07dcc2e) paused 2026-10-04T12:54:22Z before any model call, on the author's word relayed by the coordinator ("we won't have enough usage for all of that GPU-locked work."). No result exists; the GPU lock was never taken. Resume steps are in mission-control/2026-10-04-social-learning/run/PAUSED.md. Entry 22 stays valid for a resumed run; series.sh changed once (deviation D1, logged before any call).

2026-10-04 13:3xZ, MMBU lead: on hold by the author ("the remaining queued items will need to be put on hold"); FT2, PS-1 and IR-0 not run; no MMBU process holds the GPU lock; resume steps in mission-control/2026-10-02-mmbu/features/PAUSED.md.

## 2026-10-04 (UTC), entry 33

Signer: Claude Opus 5.5 (an Anthropic model), a subagent of the lead session, under the author's
2026-10-02 delegation. Zain Dana Harper did not sign personally. Governed by entry 20.

| Record | SHA-256 | Scope of the hash |
|---|---|---|
| Representation series pilot results (no bar passes; floor nulls) | 54d4ff8c7aa3c17a6b7152d3ad9f35b94d0203046e60e20af3745fda9511212b | file hash of mission-control/2026-10-04-vista-latent/RESULTS.md |
| Deviations D1 to D6 | b8aa6a48a5f513ade0e344075c66173375b88664e7545fb7d363c014851c4376 | file hash of mission-control/2026-10-04-vista-latent/DEVIATIONS.md |
| Analysis and monitor outputs | 2bcb8312876dfec63e5b951a77ac50016a462650f4723e1bfb71647d4579f882; 8d154a2fa7d86d3d22afeb35bd2d75e082c7b610a14f4048ae9b4fbd779eb573 | run/analysis.json; run/monitor.json |
| Programs as run after deviations | 5ee4a75fe715e42f58438eed89e3296869c42f11ee84706b091c07cce389d19f; 4dc3831cb830046d898e46b63d28374b08889ee522e1de2bb95012768771eeec; 1a6fde560caedd56e228dc67a72ea18294c2dc708d105c154ff4e4f9bdf199dc | run/arms.py; run/run_model.py; run/run_8b_rerun.sh |

All three Qwen3-VL sizes scored 1 to 7 of 120 levels in every arm, below the random floor of 16 to 24; every
bar reads NULL from a floor. All controls held (optimal 120/120, replay MATCH in every cell, monitor
planted controls OK). GPU lock released with an owner check at 2026-10-04T13:26:49Z. Not committed or
pushed by the signer; the lead session decides the push.

Note on entries 25 and 28 (2026-10-04, Claude Opus 5.5 subagent): paused on the author's hold before any GPU step or test-split read; no result exists under either entry. Resume steps: mission-control/2026-10-04-jev/PAUSED.md.

## 2026-10-04 (UTC), entry 34

Signer: Claude Opus 5.5, the MMBU lead session, resuming FT2 on the author's words of 2026-10-04 relayed verbatim by the
coordinator ("You can continue some of the other work."). Zain Dana Harper did not sign personally. Numbered after
reading the whole file. Written before any FT2 GPU step.

Re-check: the FT2 prereg (cdb71426...), config (a4c7e41e...), training rows (533101d1...), eval rows (71d260d6...,
b115e613...), train2.py, evaluate3.py, fieldgen2.py, tokcheck.json and run_ft2.sh all equal their recorded hashes.
Changes since entries 21, 29 and 32, none to rows, bars, arms or recipe:

| Record | SHA-256 | Note |
|---|---|---|
| Lock helper revision 4 | 42ab715cdff320930c5ea1751aea9e2cac3d255371168bdfd397fe6e806262a1 | OWNER is one JSON object; step pids in STEPS. Fixes a defect in revision 3 (6f9f995d...): its MSYS kill -0 fallback reads an unrelated MSYS pid with the same number as alive, so release could refuse; step liveness is Windows-only again, owner description keeps both checks |
| Resume wrapper | 670029a06ed0c83fc56ee8db108ee5feae5fd23c2a71d5dd04ab2a8f8114407c | train/ft2/ft2_resume.sh: waits for SHAPLEY.done, runs run_ft2.sh, scores, writes FT2.done |
| Dev scorer | a0a742a5a3e66f4f608e173633a818ef98f46adbf390fd056914ab7998f36812 | score_ft2.py (was 2354187a... in entry 21): adds a per-row output file only |
| Analysis and bar reader | e50f5c9d86d09ff684dcd98217d0d79bb47a432d53cf0e6caf1dcdd949717954; 2ecb27b59a17fe563fa97c642f74c98ac2fe7d34f2ac0f4ea6f9cf3eafd476b3 | analyze_ft2.py (reported, not gated); bars_ft2.py reads B1 to B7 as registered |

Author rulings recorded in PAUSED.md (AISSLab in; h5py for Cheng) apply to the next slice build, not to FT2, which
runs on the rows as hashed. PS-1 and IR-0 stay paused. Not committed by the signer.

## 2026-10-04 (UTC), entry 35

Dated correction by the MMBU lead session (Claude Opus 5.5). The hold logged at 13:3xZ ("no MMBU process holds the GPU
lock") was wrong in effect. At 13:3xZ I stopped the FT2 waiter with taskkill //T on Windows pid 22140, the outer
bash started by PowerShell. Its child, the MSYS bash running run_ft2.sh (MSYS pid 229484, Windows pid 9228), survived:
taskkill's tree walk did not reach the MSYS process, and I checked only that 22140 was gone. That waiter took
D:/gpu.lock.d at 13:46Z (token mmbu-ft2-229484-1791107855) and ran FT2 steps during the author's hold. It runs the
hashed prereg (cdb71426...), config (a4c7e41e..., rows 533101d1...) and run_ft2.sh (91535676...), with lock helper
revision 3 (6f9f995d...) as sourced at launch. The coordinator found it. The duplicate resume process of entry 34
(Windows pid 36040, MSYS pid 298211) was killed before taking any GPU step, by Windows pid and then by MSYS pid.
The surviving run writes no FT2.done; scoring after PIPELINE DONE is train/ft2/ft2_postrun.sh
(26a034b2228aadb33a6df978132306c9d3fc1495957afef31f371b1053c44767). Known risk: revision 3's release can refuse
on a false-alive step pid (entry 34); if the lock stays after PIPELINE DONE, a human checks STEPS pids with tasklist.
Fix for future stops: kill MSYS scripts by MSYS pid as well, and confirm with ps -ef, not only tasklist.

## 2026-10-09 (UTC), entry 37

Signer: Claude Opus 5.5, the MMBU lead session, under the author's 2026-10-02 delegation and the author's words of
2026-10-09 relayed verbatim by the coordinator ("Continue all work."). Zain Dana Harper did not sign personally.
Numbered after reading the whole file: it ends at entry 35. STATUS-2026-10-04.md and 2026-10-03-OPEN-WORK.md cite an
"entry 36" (the PS-1/IR-0 queue correction) that is not in this file; 36 is left to that record, and this is 37.
Written before any B4 GPU step and before the 4B weights are downloaded.

| Record | SHA-256 | Note |
|---|---|---|
| B4 pre-registration | 756c9c2776a012c9c5ca3f9b685c6b133d8f4405ecf4c4a808cd7d4160f78ea2 | train/b4/PREREG-B4.md: Qwen3.5-4B base comparison, bars Z1 and C1 to C9, change triggers |
| B4 config | ba251c8f7fb625eb9527e2dac9c9281d25189680192c3006f30dda41c5fe00cc | FT2 recipe; out_dir and prereg differ only |
| B4 runner | 79673ff4f241146bc1ab46336375933dc0a8dd8c9f924d917cdd97a9998438a1 | train/b4/b4_run.py: existing runners with the MODEL pin replaced |
| FT2 config, rows, eval rows (unchanged) | a4c7e41e...; 533101d1...; 71d260d6...; b115e613... | re-hashed 2026-10-09, equal to entry 21/29 |
| Baseline scores, dev 94126985 | c0580d7134ea36b3343afc2725f5b02cb81504d7af0c8cd8efa5dbdd5f6c7627 | devdiff/newrev_scores.json (score_newrev.py 8a9e71d7...) |
| Regenerated Pass 1 runs | 5e81d297...; 9e190023...; 9143a823... | A2r, FT1r, FT2r on 94126985 |
| Slice 3 inventory snapshot | 59323ea896234148ce195098eadbed970c488258cea660ed6cdc7da4dd9ec333 | 14,601 verified files, line hash b21ed445...; 29 complete, 3 partial |
| Rules brief, live | 68fb4c2685d3d3b501da6f92f0906f970d851b596e98fddede26fb6e2b6e4ba0 | fetched 2026-10-09T01:02:23Z; P_max 4.66B (Qwen3.5-4B), alpha 0.1 |
| 4B base pin | Qwen/Qwen3.5-4B @ 851bf6e806efd8d0a36b00ddf55e13ccb7b8cd0a | 4,659,865,088 params, 9,342,907,469 bytes; download awaits the author's approval |

Scoring programs for B4 (score_b4.py, bars_b4.py) are hashed in an amendment before Stage 1; an amendment may add a
check and may not change a bar, an arm or the recipe. Not committed by the signer.

## 2026-10-09 (UTC), entry 38

Amendment to entry 37 (B4), by the MMBU lead session (Claude Opus 5.5), before any B4 GPU step. Download approval:
the author, 2026-10-09, relayed verbatim by the coordinator: "Also you have permission to install." No bar, arm, row
or recipe changes.

Stage 0 results: all 14 files of Qwen/Qwen3.5-4B @ 851bf6e8 match the hub (3 LFS files by SHA-256, 11 by git blob
SHA-1; fetch_4b.json). params_loaded 4,539,265,536 (at most the hub's 4,659,865,088; the loaded model omits weights
the generation class does not build), so m(4B) = 1.00264; 200 LoRA layers match. tokcheck with the 4B processor:
11,172 of 11,172 rows within max_len 2048 (longest 883 tokens), 5,372 task and 5,800 context replies strict, 0 failures.

| Record | SHA-256 | Note |
|---|---|---|
| score_b4.py | dc41cf1f5a731bb83bf87ca41e3347e2624c22d7dd02e9a7ecc85011d7e22fcf | reads Z1 and C1 to C9; replaces the "bars_b4.py" named in entry 37 (one file) |
| Smoke test of score_b4.py | train/b4/smoke/ | 2B replies standing in for the 4B arms reproduce FT2's B1, B2, B3, B7 and the rescore exactly; outputs moved aside, stand-ins deleted |
| run_b4_stage1.sh | 796c38dcaeef37760d19e34ff191a1ad0d0cad8879fa132df731df5ba52a91f8 | Z4: dev task, dev context, held-out, in-source |
| run_b4_stage2.sh | 92471df778ea6492d950d822076f2f4f02a22fa710440ac1b23c87b4bc30acbe | refuses unless bars_b4_zero.json shows Z1 passed |
| tokcheck_4b.py; tokcheck_4b.json | 6b298c701cd0bc3d39a98b17fffba5a940c5b2ce84f496b8d0909c6aff14cf0c; 69c373bb604c6dbcf4de2ce1beb84a3432269fd9792e720fd6d9ff718f5a6f40 | train/ft2/tokcheck.py unchanged, 4B processor |
| fetch_4b.py; fetch_4b.json | 23d1fe2e8f64030c2eeda95bcc5b5229a4e79a4a906b579be7fada31fa0eced1; d4a5d673c299061dd484c276e45a16c51159a25118905bfb45a7ca3bc7e8dd1f | download and per-file verification |
| Lock helper | 42ab715cdff320930c5ea1751aea9e2cac3d255371168bdfd397fe6e806262a1 | revision 4, unchanged |
Not committed by the signer.

## 2026-10-09 (UTC), entry 39

Amendment to entries 37 and 38 (B4), by the MMBU lead session (Claude Opus 5.5), before any scored B4 output exists.

What happened: Stage 1's first step (z4_dev_task, lock token mmbu-b4s1-20229-1791518798, 04:06:38Z) wrote no row in
10 minutes with the GPU at 23.8 GB. I stopped it (taskkill /T on the step tree; the script released the lock at
04:17:24Z). A timing probe (token mmbu-b4probe-22968-1791519461, released 04:36:05Z) generated 36 dev replies at batch 8
and 4, outputs not scored. 23 of 32 hit the 768-token cap; every reply opened with reasoning text.

Cause: the two chat templates differ. Qwen3.5-2B renders a non-thinking turn by default ('<think>\n\n</think>\n\n');
Qwen3.5-4B @ 851bf6e8 opens a thinking block by default ('<think>\n'). The same runner call therefore gave the 4B a
different prompt from the one every 2B arm received, in evaluation and in training (tokcheck under entry 38 showed rows
2 tokens shorter than FT2's for that reason). Entry 37's statement "Prompts ... are the 2B runs' own" was not true of
the rendered text.

Fix: every B4 mode renders with enable_thinking=False (b4_run.py wraps ProcessorMixin.apply_chat_template). New CPU
check `b4_run.py tmpl`: over 20,803 prompts (538 distinct: dev 94126985 both passes, training rows, held-out and
in-source rows) the 4B render equals the 2B's own default render byte for byte, 0 differ; the unpatched 4B render
differs (control). tokcheck rerun with the fix: longest rows 885 / 763 / 725 / 590 tokens, equal to FT2's, 0 failures.
This restores the arm entry 37 described; no bar, row, recipe, decoding cap or threshold changes. The probe replies
and the superseded tokcheck are kept in train/b4/superseded/.

| Record | SHA-256 |
|---|---|
| b4_run.py (was 79673ff4...) | a57e274197db04ede556d1f216de9eaabca1845351feab6cc8abf4a146fd0cc8 |
| tokcheck_4b.py (was 6b298c70...) | 64ba235d3aa884568df1cb7531893d7353243f3f94d9500cc01aa4aebf025092 |
| tokcheck_4b.json (was 69c373bb...) | 8ea41df475f3cdd6393b60c1860045d0bac0ce239097415b487d57261f5500a1 |
| score_b4.py, run_b4_stage1.sh, run_b4_stage2.sh | unchanged from entry 38 |
Not committed by the signer.

## 2026-10-09 (UTC), entry 40

Operational amendment to B4 (entries 37 to 39), by the MMBU lead session (Claude Opus 5.5). No bar, arm, row, recipe,
prompt or decoding cap changes. Stage 1 attempt 2 (token mmbu-b4s1-25815-1791520598, 04:36:38Z) ran with the 2B runs'
generation batch of 16. With the non-thinking render the replies were normal (144 rows, median 125 new tokens, 1 at
the cap) but the 4B at batch 16 filled the card (23.8 GB) and one batch made no progress for over 20 minutes. I
stopped the step by tree at 05:07:49Z; the script released the lock at 05:07:50Z. The 144 replies are set aside in
train/b4/superseded/attempt2_batch16/ and are not scored. Generation batch for every B4 evaluation step is now 4
(probe: 14.8 GB peak, no stall). Greedy decoding is batch-independent except for left-padding noise, which the dev
rescore control already measured for the 2B (STATUS-2026-10-09.md). Training batch stays 1 with accumulation 16.

| Record | SHA-256 |
|---|---|
| run_b4_stage1.sh (was 796c38dc...) | a876a5a70597b1df700ff8ad7a8bc04f952983401ee18f38bb23365d738123a1 |
| run_b4_stage2.sh (was 92471df7...) | see the line below |
| run_b4_stage2.sh, train step without a batch flag | 534532d22f728d6f05bdb59b492446a788efcb1a650e5dc2a75bd19c9b2109f5 |
Not committed by the signer.

## 2026-10-09 (UTC), entry 41

Operational amendment to B4, by the MMBU lead session (Claude Opus 5.5). No computed value changes. From about
07:00Z the Stage 1 generation process (Windows pid 33076, step z4_dev_task) ran at about 0.1 core: one batch of 4
took 16 minutes, the GPU sat at idle clocks, and the process was not paging. Windows execution-speed power throttling
(EcoQoS) on the idle session is the cause: after a per-process opt-out (SetProcessInformation,
ProcessPowerThrottling, ControlMask 1, StateMask 0) applied at 07:29Z, the same process used 34 CPU-seconds in 30 s
against 3.4 before. No system setting or power plan was changed. b4_run.py now applies the same opt-out to itself at
start (every later B4 step); the opt-out changes scheduling only. Greedy outputs do not depend on speed.

| Record | SHA-256 |
|---|---|
| b4_run.py (was a57e2741...) | f493f1735c56ead9c6862b49524f4d8ef8d95dcc5b200e66d4549f3a0b54cc35 |
Not committed by the signer.

## 2026-10-09 (UTC), entry 42

Deviation record for B4 Stage 1, by the MMBU lead session (Claude Opus 5.5), on the author's word of 2026-10-09
relayed verbatim by the coordinator: "continue". The desktop app restarted and stopped this session. Stage 1
(token mmbu-b4s1-32509-1791522507) died during z4_dev_task with 1,452 of 3,126 dev replies written (last log write
about 07:44Z); all 1,452 lines parse, 1,452 distinct unique_ids, file SHA-256 below. The lock stayed with my OWNER and
a dead pid (4468; step pid 45460 dead). I released it by token check at 14:30:27Z; the OWNER copy is in
train/b4/superseded/stale-lock-OWNER-2026-10-09T0519Z.json.

Resume, not restart: run_model_v3.py appends and skips every unique_id already in Z4_task.jsonl, then runs the
remaining rows in dev metadata order at batch 4. Which rows remain is fixed by the file; the deviation from an
uninterrupted run is batch composition for the remaining rows (greedy decoding with left padding; the 2B rescore
control measured that effect as reply-level, not score-level). The step's meta file from the first part is kept in
train/b4/superseded/Z4_task.meta.attempt3_part1.json because the resumed step rewrites it. GPU order: the
engine-explainers media job takes the lock first; Stage 1 resumes after its release.
| Z4_task.jsonl at resume (1,452 rows) | bcc733215118de9279fa4106cbb6c00a3d806548e6f3cee82db9e306df23e41f |
Not committed by the signer.

## 2026-10-09 (UTC), entry 43

Second deviation record for B4 Stage 1 (MMBU lead session, Claude Opus 5.5), on the author's word relayed by the
coordinator that all work continues. The desktop app restarted again (about 23:00Z per the coordinator; the run's
last progress line is 244 of 1,674 remaining rows, about 15:00Z). Stage 1 (token mmbu-b4s1-2115-1791556250) died in
z4_dev_task with 1,696 of 3,126 replies written, all parsing, all distinct (SHA-256 ecbda0f4b334d0977036521525223e0178df7a2fcc98c236d7d82daabdd1ad0b). Its pids (32104, 35652) were
dead; I released the lock by token check at 2026-10-09T23:11:01Z. Resume by the entry 42 skip rule. Cause of both deaths
(inferred): the GPU script ran as a child of the app session and died with it, while the slice 3 download chain,
started with nohup, survived. The resumed script runs under nohup, detached from the session.
Not committed by the signer.
Correction to entry 43, same session, minutes later: the nohup download chain did not survive either (no
resume_chain2.done; core-resume3 was restarted at 14:30Z by another session). The resumed Stage 1 was instead launched
through WMI Win32_Process.Create (one process, outside the app's process tree; no scheduled task or other persistent
configuration), Windows pid 32744.

## 2026-10-10 (UTC), entry 44

Third deviation record for B4 Stage 1 (MMBU lead session, Claude Opus 5.5). Correction to the coordinator's relayed
state of 12:00Z: Stage 1 did not finish. Its last write was 2026-10-10T05:41:25Z, during z4_heldout2 (context pass,
508 of 1,006), when the machine-wide event that also broke this session's shells stopped the WMI-launched run.
Dev Pass 1 and Pass 2 for Z4 were complete (3,126 each). Held-out: 1,801 of 2,299 replies, all distinct row ids
(SHA-256 dbce6fb26be77308c629732f497aa3545f615b7071aa6dc93599c186af3d5137); in-source: none. The stale lock (dead pid 13232, token mmbu-b4s1-837-1791587474) was saved and released
by the coordinator at 12:10Z.

Gate Z1 reads dev only. Read on CPU at 03:3xZ: Z4 minus A2r dev T_em +0.011 [0.001, 0.021], met. The margin is thin:
the lower bound is 0.001, and the 4B zero-shot dev replies were produced in three resumed segments (entries 42, 43),
so batch composition differs from one uninterrupted run. C1, C3 and C7 need the Z4 held-out replies, so Stage 1 is
finished before Stage 2 by the same skip rule (evaluate3 gen skips answered row ids).

run_b4_chain.sh (355b84802ef2c0002cd239617c3e6059442e89be916da9c8bbbcf42fce475e94) runs Stage 1 to completion, score_b4.py zero, Stage 2
(which refuses unless bars_b4_zero.json shows Z1 met), then score_b4.py full. It starts after the shader queue's
gpu_queue.done, outside the app's process tree. Not committed by the signer.

## 2026-10-10 (UTC), entry 45

B4 Stage 1 complete (MMBU lead session, Claude Opus 5.5). The chain of entry 44 finished Stage 1 at 13:34:51Z
(token mmbu-b4s1-3403-1791634766, released by token 13:34:52Z) and scored it: bars_b4_zero.json
(64caaa0d762d0c91253d6c05463966ff402175b7f0c47bcae9fe850e2ebab453). Z1, dev T_em Z4 minus A2r: +0.01088
[0.00128, 0.02079], met; thin margin, as entry 44 says. Reported, held-out answer: Z4 0.181 [0.156, 0.209], FT2 (2B)
0.230; FT2 minus Z4 +0.050 [0.029, 0.072].

Defect, mine: run_b4_stage2.sh's gate check passed an MSYS path (/c/...) to Windows Python, which raised
FileNotFoundError, so the script printed "GATE Z1 NOT PASSED" and refused although Z1 was met. No GPU step ran. Fixed
by giving Python the C:/ path; checked on the real file (exit 0). run_b4_stage2.sh is now
6d92f84d6fbad72819ae87c80fc3087f1d7afda73b21bdadb082d60db213d7b2; run_b4_chain2.sh
(7f99eef1d7d67dc129d55c7c81ee7c7aeb7358a694fa4e93cbb3deb6cb7a2848) runs Stage 2 then score_b4.py full, launched through WMI.
Not committed by the signer.

## 2026-10-10 (UTC), entry 46

Operational amendment to B4 Stage 2 (MMBU lead session, Claude Opus 5.5). No value-affecting change. The first
FT2-4B training attempt (token mmbu-b4s2-28008-1791639342, 13:52:53Z) ran 40 optimizer steps at about 11 s each, then
stalled for over 20 minutes with the card at 23.8 GB and 100% busy: the caching allocator outgrew the 24 GB card and
the driver spilled to system memory. No checkpoint existed (first at step 100). I stopped the step by tree at
14:22:30Z; the script released the lock by token. Its train log is kept in train/b4/superseded/.

Fix: b4_run.py train mode caps the process at 22.5 GB (torch.cuda.set_per_process_memory_fraction), and
run_b4_stage2.sh sets PYTORCH_CUDA_ALLOC_CONF=garbage_collection_threshold:0.8. The allocator reclaims cached blocks
before the cap; a real overrun raises OOM and the rerun resumes from the last checkpoint. Training restarts from step
0 with the same seed and order. No driver or system setting was changed.

| Record | SHA-256 |
|---|---|
| b4_run.py (was f493f173...) | 1092bfd2780a38a2145ea3c898d6f2d843c7ae2a2b2b4ab3cce285a962aa6e2a |
| run_b4_stage2.sh (was 6d92f84d...) | a007c6c4e2fe45f6723566d0449d78079e60e02c2c9f317f8ef3123e67c44ac0 |
Not committed by the signer.

## 2026-10-10 (UTC), entry 47

B4 result (MMBU lead session, Claude Opus 5.5). Stage 2 ran 14:22:56Z to 19:47:26Z under token
mmbu-b4s2-39588-1791642175 (released by token 19:47:30Z). FT2-4B lora_state
106bbc71031c3cbb01db671b72032b076fb82fb1148863796e091d9a60897788 (698 steps, 6,881 s). Bars file
bars_b4_full.json 0c6b9c9bea24186d9a9ad14d79d439095c3c041e29745fbb0acd0f6d3f19f632.

Met: Z1 (+0.011 [0.001, 0.021]), C1, C2, C3 (6 of 6 fields), C8 (dev T FT2-4B minus FT2r +0.015 [0.004, 0.025]).
Missed: C4 (Pass 2 shell 0.9898), C5 (+0.006 [-0.004, 0.017]), C6 (+0.007 [-0.0001, 0.015]), C7 (-0.020 [-0.031,
-0.006]), C9 (adjusted dev S +0.005 [-0.004, 0.013]). Change trigger 2: the submission-informing run stays on the 2B;
the 4B is the Track 2 reference. Margins on Z1 and C8 are thin (lower bounds 0.001 and 0.004) and Z4 dev replies came
from resumed segments. Not committed by the signer.

## 2026-10-12 (UTC), entry 48

B4 reading and decision, dev error diagnosis, and the JP1 judge proxy (MMBU lead session, Claude Opus 5.5), under the
author's 2026-10-02 delegation and his words of 2026-10-12 relayed verbatim: "I'd like to follow up and revisit and
check progress on the the biological training model for the MMBU project. That is a primary focus, and so that's
something that we're going to be wanting to work on consistently over the next couple months."

B4 read by PREREG-B4.md (bars in entry 47): Z1, C1, C2, C3, C8 met; C4, C5, C6, C7, C9 missed. Trigger 1 not met
(C9); trigger 3 not met (C8 met). Trigger 2 applies: the submission-informing run stays on Qwen3.5-2B; FT2-4B is the
Track 2 reference, reported only. Owner of the decision: the author.

Reported, not a bar: with JP1 in place of exact match, the C9 analogue is +0.012 [0.0008, 0.0229] and C8's analogue
+0.028 [0.014, 0.041]. JP1 was written and frozen (self-test 10 of 10) after the B4 result and before a blind hand
check of 180 dev rows graded by this session (agreement 175 of 180, kappa 0.91, 32 of 32 accepts correct, 5 of 148
rejects rescued). The B4 decision is not changed by this re-read; the next preregistration names JP1 at this hash as
its primary answer score.

| Record | SHA-256 |
|---|---|
| diag/judgeproxy.py (JP1, version jp1-2026-10-12) | e97a17950c0051eb0a4ed7b29ab66d2621af79700ad4d10d29ec1c7a0f088864 |
| diag/diagnose.py | a475793b05916487f87a71e9239c85f8c76947f56a3c7e49711d39cdc2a83ba5 |
| diag/vocab_cover.py | 9b5af44f0c640a498da1769ecc68490ad040a178b238d3e5282edbc9bc8b5368 |
| diag/jp_reread.py | bbaa2aceea70f7765749c5e0759405e381c6f49e3f755503d6418fe9295951f7 |
| diag/handcheck_sample.jsonl (seed 20261012) | a4c0dcddec8780715a6ca3b034ad721a6b0cce452fb5da74a7eda031547c4f7c |
| diag/handcheck_grades.json | 829263f230086ba522c9cd24bdc091caa1fb1e6f41dc3600dda8aeb3242b0605 |
| diag/diagnosis.json | 9a2a20fdc3f55fc31dda6299385531c5ee58f04f6ac52e8918604ed44534ed1b |
| diag/jp_reread.json | c920f97aec28888123fbacf0926daafbebc5ee20b82458187a56d087734141df |
| diag/vocab_cover.json | 05ceeaa35af84845b30a5e0a03080edfa5907472c8b590a90a61caa7cb7da079 |
| Rules brief, live 2026-10-12T19:46Z (unchanged) | 68fb4c2685d3d3b501da6f92f0906f970d851b596e98fddede26fb6e2b6e4ba0 |
| Challenge site, live 2026-10-12 (adds a "MMBU Public Data" link only) | d2b2d6e94bc4dbf6d1dd12293e8a630c06edc801c048465a66382882cf6078fe |
| devdiff/refresh_dev.py (dev refresh, d09ff622) | a045288b5c354d5d767c939f6d9f43bd6379c1662c3a6f88efeaf8a7eac686a8 |
| devdiff/run_refresh_d09ff622.sh | 6e7a99a040544142e64de9791374973ccb976763edb603adcd81f43de3f2337d |

Dev set head moved to d09ff6223a6cbb9b3a97202c7c2ab72da2b615e0 (2026-10-12 16:42 UTC). The refresh regenerates only rows
whose image or rendered prompt changed and is reference evidence only. Dev reads in this entry are analysis and
scoring; no dev text, label or verdict enters a training row. Not committed by the signer.

## 2026-10-12 (UTC), entry 49

Operational record (MMBU lead session, Claude Opus 5.5). No computed value changes.

1. Dev revision d09ff6223a6cbb9b3a97202c7c2ab72da2b615e0 pulled to D:/datasets/mmbu-dev-d09ff622 (3,107 files, 0 missing;
   manifest 0dd13042..., metadata.jsonl f69a94c95c21cac52e645ebfa5f1cac5728818018a57f1d45d90f03193be6b8f). Diff against
   94126985 (DIFF-D09FF622.json 94a92be8...): 3,103 rows; 56 removed, 33 added, 711 changed (370 answers, 318 options,
   484 questions, 104 images, 67 with metadata changes); 137 image hashes not in the old revision. These new images
   have not yet been checked against slice 1 and 2 training images (queued, CPU).
2. Defect, mine (b4_run.py, entry 41): the in-script EcoQoS opt-out called SetProcessInformation without restype or
   argtypes, so the GetCurrentProcess pseudo handle was truncated and the call failed; the B4 logs print "opt-out
   failed: 0" in Stage 1 and Stage 2 steps. Only the external opt-out of 2026-10-09 07:29Z was ever applied. Speed
   only; greedy outputs do not depend on it. Fixed in devdiff/refresh_dev.py (typed call, c11a36ce...) for every later
   step; the running A2r_task step (winpid 60456) was opted out externally with diag/ecoqos_optout.py (f5faeffc...).
   b4_run.py is not in use and is left as hashed in entry 46; any reuse must take the typed call.
3. Dev refresh launched 2026-10-12T20:06Z through WMI Win32_Process.Create (bash pid 39804), lock token
   mmbu-refresh-6338-1791835562 taken 20:09:03Z. A2r task: 2,567 replies reused by image and prompt hash, 536 to run.
Not committed by the signer.

## 2026-10-12 (UTC), entry 50

Dev refresh result on d09ff622 (MMBU lead session, Claude Opus 5.5). Reported numbers, not bars. The refresh ran
20:09:03Z to 20:51:02Z under token mmbu-refresh-6338-1791835562 (released by token 20:51:04Z); 536 task and 137
context rows regenerated per arm, the rest reused by image and prompt hash. Scores (diag/score_d09ff622.py
75f4657a..., output diag/scores_d09ff622.json b13b7fda...), 3,103 rows, row bootstrap seed 20261002:

T_em: A2r 0.103, FT2r 0.106, Z4 0.117, FT2_4B 0.130. T_JP1: 0.168, 0.157, 0.186, 0.198.
FT2_4B minus FT2r: T_em +0.024 [0.014, 0.034]; efficiency-adjusted S on exact match +0.012 [0.003, 0.020]; on JP1
+0.022 [0.011, 0.033]. Z4 minus A2r T_em +0.014 [0.004, 0.024].

Reading: B4 was preregistered on revision 94126985 and its decision (trigger 2, stay on 2B) is not re-read here. On
the organizers' corrected revision the C9 quantity would be met under both scorers. The next preregistration (FT3)
therefore carries both bases with C9 read on d09ff622, and its trigger, not this entry, picks the submission base.
Selection on dev is reported as selection-biased beside the unselected Z4 and FT2r references.

| Record | SHA-256 |
|---|---|
| A2r task / context | 3be76de374af496be7820878ad0f191d18c688a9cb685ed5fc2f2ca6ef83aa6e / f1ffbba5fcf1603ab5bd0956b42b34133e53a19f1379ae38ec5ce9d1ce3d62cd |
| FT2r task / context | a131a7b207f74aac2e124e230ce41011c17e955a288d011fc03bc90554fd4ceb / bd7c8e63115c4ac163989155dbd8fd95004784605c2286d3b2004385bb01ea8b |
| Z4 task / context | bcc7a9b759216b2692433cb263cb837ce168df4070837be31561883b3e506211 / 78eda44202963b75b8f34eff6251e8e524cff013f15f496d777be0e3839a62f4 |
| FT2_4B task / context | 7bd763fdef8f2efe3db711443b4f5f9bb293441fbaceeecc8c2e82ddbece812b / 1984df3f9d7ab6429c9650a372d78a0287f35e8c8396e00fa21f3f03420d2d7f |
Not committed by the signer.

## 2026-10-12 (UTC), entry 51

FT3 preregistration (MMBU lead session, Claude Opus 5.5), under the author's 2026-10-02 delegation and his words of
2026-10-12 quoted in entry 48. Written before any FT3 GPU step. Arms FT3Q_4B, FT3Q_2B (submission-informing, Q1 rows
only) and FT3A_4B (research, all tiers, never submission-tagged); bars G1 to G6; G3 (adjusted S on JP1, FT3Q_4B minus
FT3Q_2B, dev d09ff622) picks the submission base. Slice 3 build (BUILD-SLICE3.md): 28 sources built, train rows
c3dae3242cef7d4b7f60be33bdad934add774bba17f105dbcfb2a7cd52666fac, twice-built identical; lead rulings on its flags
are in the prereg. Quarantine of slice 1 and 2 training images against the 137 new d09ff622 dev images: 153
candidates, 1 confirmed (an NIH_CXR14 image, dropped; FT2 and FT2_4B trained on it, so dev row 41d23a8f... is excluded
from every FT3 comparison).

| Record | SHA-256 |
|---|---|
| train/ft3/PREREG-FT3.md | 92704389e8663f95d931a8f2ab96ab04a879ae1938e91fd5e8235f5725f05282 |
| train/ft3/ft3_run.py | 4a2bbd4fbcfa3ff14df24da2f6ad1951337ebe3df6bd87e01df8f63dd1a1994e |
| train/ft3/score_ft3.py (smoke-tested on the reference arms) | 7d733d58c826b550554213508c95f8d61f6c4c8e0d0c0a00c65d89c45f3b947d |
| train/ft3/build_rows_ft3.py; rows_ft3_report.json | 6bea52f11b691d0abe709ffcac6290c1698e84cb67f3d81a1b470380b1880c5d; 9cb6ff2364c47bf5996b19ea892ed72280403f31a6fcfb9f963550700510de26 |
| train_rows_ft3q.jsonl (17,059 rows) | 84055f7f694b31352b3935e24530dd629b25255c772807bc2fccd15f9a12d86a |
| train_rows_ft3a.jsonl (21,996 rows) | 91dc8cf9c339ba8b9504741f68744ae3c98767df511887b7aa7835580a713858 |
| configs ft3q_4b / ft3q_2b / ft3a_4b | fa8df533e0c646139693c3b2848e9ba17c35336959073b639417fda1312b8e6e / d8a24cf10a2a063ab66bbf722cbaad69e89a73eee21acfada7be379086e33cf5 / d58abf7d31327318a2ba743a3c8798815d5c3b9c91689735b1d6834519e5fefe |
| run_ft3_arm.sh; run_ft3_chain.sh | 335b5e722aacdb2fbeef7c393de506294009019b222450977c1b73a848700521; 8c0d1f49784a0ce82498b19405dd9e0bfde3d0dce383f0f21692f55463755519 |
| diag/quarantine_d09ff622.py; .json | afd93bb8aee9bfd7916dfe62fab4215f6828250d7b703f64de106ecca70437d3; 48c84ccbfdf292b9e6c3cedfe20d5433e1df2ef7cf7435deafd93d2b1a467d82 |
| diag/judgeproxy.py (JP1, unchanged from entry 48) | e97a17950c0051eb0a4ed7b29ab66d2621af79700ad4d10d29ec1c7a0f088864 |
Not committed by the signer.

## 2026-10-12 (UTC), entry 52

FT3 launched (MMBU lead session, Claude Opus 5.5) through WMI Win32_Process.Create, chain bash pid 36332, outside the
app's process tree. Arm FT3Q_4B took the lock at 21:56:15Z (token mmbu-ft3-ft3q_4b-15007-1791842175, owner bash
32832), training python 51380, 1,066 optimizer steps at about 9.3 s each. Each arm holds and releases the lock by token;
the chain then runs score_ft3.py (hash in entry 51). Not committed by the signer.

## 2026-10-13 (UTC), entry 53

Author decisions and FT3 amendment 1 (MMBU lead session, Claude Opus 5.5).

Author decisions, recorded by the coordinator at mission-control/2026-10-02-mmbu/AUTHOR-DECISIONS-2026-10-13.md,
SHA-256 eef4d19e1078173a891ce5c344aeff295f4660300299055e68667f2b1ebddbf9. Author, verbatim in chat 2026-10-13: "my
permission. To train on the public source data sets that MMBU draws from. I believe written permission was given. And
then the data sets with the conflicting licenses, we're not doing anything commercial, so that's okay. And then on
Discord, let me see if there was any organizer announcements. So the public data set got a round of improvements on
October 9th. All data sets are acceptable as long as disclosed." Effects: (1) I-2 is relaxed by this dated author
approval: Q2 sources (MMBU's public source datasets, train splits only, quarantined against dev and official test
splits) may enter submission-informing training; the organizers' 2026-10-04 words were "You may train on images from
public datasets." (2) RIVA_PAP and REAL_COLON may be used on a non-commercial basis, each archive's own licence text
recorded in the data disclosure. (3) Every training source is listed in a data disclosure kept current for submission.
The "October 9 improvements" are inside the dev revision change already pulled: the hub commits on 2026-10-08 23:21Z to
2026-10-09 05:37Z (MGMT relabel, 31/30 swap with the private set, tuberculosis boxes, 95 label fixes) lie between
94126985 and d09ff622, which also adds the 2026-10-10 and 2026-10-12 commits (confirmed from the hub commit list).

FT3 death. Arm FT3Q_4B (token mmbu-ft3-ft3q_4b-15007-1791842175) stopped between 22:20:50Z (step 160 of 1,066 logged)
and 22:22:20Z (next step due). The whole tree ended at once: no "END", "STEP FAILED" or trap release line in the arm log,
an empty chain log, the lock left with dead owner pid 32832. Excluded as causes: a checkpoint save (step 100 saved at
22:11Z; next due at step 200); a Python error (none logged); GPU OOM (process capped at 22.5 GB, and a Python OOM would
leave bash to log END); a WMI job object (tested 2026-10-13: a WMI-created process is not in a job, parent WmiPrvSE);
an OS event (System and Application logs hold nothing between 22:15Z and 22:30Z). No other workstream's script kills by
image name. Cause: an external kill of the whole process tree, source unknown. Same signature as the 2026-10-10 05:41Z
B4 stop. Windows rebooted 2026-10-13 01:25 local. Stale lock released by token check 08:53:50Z; OWNER copy
train/ft3/stale-lock-OWNER-2026-10-12T2220Z.json (7f9f893f...). Checkpoint at step 100 (9d66efee...) is the resume point.

Amendment 1 to entry 51 (FT3), before the restart. No arm, row file, recipe value, bar or scorer changes.
- ckpt_every 100 -> 50 in all three configs (ft3q_4b 4af5cb4f..., ft3q_2b c5fb3066..., ft3a_4b 3b83d282...): an
  interruption loses at most about 8 minutes of 4B training. Resume restores LoRA weights, optimizer state and data
  position; dropout RNG is not restored (as in B4).
- Watchdog train/ft3/ft3_watchdog.ps1 (fde0e57d...), PowerShell, launched through WMI: relaunches the chain if it dies
  without finishing, after releasing a stale mmbu-ft3- lock whose owner pid is gone; stop file train/ft3/FT3.stop. It
  installs nothing persistent and does not survive a reboot. A logon-triggered scheduled task would; it is persistent
  configuration, so it is prepared, not registered, until the author approves it.
- E2 fold-in: FT3 runs as preregistered. FT3A_4B's status changes from research-only to submission-eligible under the
  author's approval; its rows already contain the Q2 sources. Trigger 2's branch "the lead asks the author" is resolved
  in advance: if G5 is met, the submission-informing set is all tiers. RIVA_PAP, REAL_COLON, DERM12345 (after an id
  map) and the unbuilt sources enter the next row set (FT4), not this run, so FT3's comparisons stay attributable.
Not committed by the signer.

## 2026-10-13 (UTC), entry 54

FT3 cause of death found, launcher replaced, shutdown save added (MMBU lead session, Claude Opus 5.5), under the
author's standing rule relayed verbatim by the coordinator, 2026-10-13: "Just make sure everything saves and resumes
at shutdown and startup", "At all times". No arm, row file, recipe value, bar or scorer changes.

Cause (found by the coordinator, confirmed here). run_ft3q_4b.log ended at step 860 (2026-10-13 about 20:30Z) with
"forrtl: error (200): program aborting due to window-CLOSE event": the Intel Fortran runtime loaded with the
numpy/torch stack installs a console control handler and aborts the process when the console it inherited closes.
The bash chain then died on cygwin fork errors. The same mechanism fits the 2026-10-12 22:20Z and 2026-10-10 05:41Z
deaths (no error line there; stdout was already gone, inferred). The author reports that the workstation is also shut
down by others in the household, so OS shutdowns are a second cause. Entry 53's statement "cause unknown" is
superseded. Watchdog defect, mine: ft3_watchdog.ps1 logged only on events, so a stuck or blind loop was silent.

Fix.
1. FOR_DISABLE_CONSOLE_CTRL_HANDLER=1 in every MMBU runner before torch or numpy load (ft3_run.py db8a820c...,
   b4_run.py 29d6cd7f..., refresh_dev.py 4448b2a0...) and in every child environment.
2. No console anywhere: driver train/ft3/ft3_chain.py (dd42fcbd...) runs under pythonw.exe and starts each step with the
   base interpreter (venv selected by __PYVENV_LAUNCHER__, no launcher process), CREATE_NO_WINDOW |
   CREATE_NEW_PROCESS_GROUP; same arms, steps, order, lock protocol (atomic mkdir, JSON OWNER, release by token only
   when step pids are gone) and skip rules as run_ft3_arm.sh; 30 s heartbeat file; it releases a stale mmbu-ft3- lock
   whose owner and step pids are gone.
3. Save on shutdown: train/ft3/train3.py (f8e47068...) is train2.py's loop (39 differing lines in train(), all the
   guard, the save helper and a log field; float(loss.detach()) replaces float(loss), same value) plus
   train/ft3/shutdown_guard.py (2e81ceca...): a console control handler and a hidden window (WM_QUERYENDSESSION,
   WM_ENDSESSION) set a flag; the loop checks it after every micro-step, saves the last completed optimizer step's
   full checkpoint (LoRA and optimizer state), logs its SHA-256 and write time, and exits 75; the driver releases the
   lock and exits; the watchdog relaunches.
4. Watchdog train/ft3/ft3_watchdog.py (e1ee1918...), pythonw: checks every 60 s, alive = driver pid exists and heartbeat
   younger than 10 minutes, a hung driver is stopped and relaunched, a check line every 10 minutes at least. The
   MMBU-FT3-resume logon task (registered earlier under the author's standing rule) now starts this watchdog.
5. Stale lock mmbu-ft3-ft3q_4b-820-1791922586 (pid 27744 confirmed gone): the old watchdog had relaunched at 20:32:31Z
   under token mmbu-ft3-ft3q_4b-1144-1791923551 before it was stopped; that bash chain ran to the step 900 checkpoint
   (51496b78...) and was stopped at 20:41Z; the new driver released its lock (owner and step pids gone) at 20:41:51Z.

Tests.
- Console close: two parents each in a new console, each starting a child that imports numpy and torch; old pattern
  (inherits the console, no env var) against new pattern (CREATE_NO_WINDOW, env var). WM_CLOSE to both consoles: the
  old child died within 5 s; the new child ran to its end (closetest/, parent.py e15df9fd..., grandchild.py d4b1dbbe...).
- Simulated shutdown on the live FT3Q_4B run (pid 34388): WM_QUERYENDSESSION then WM_ENDSESSION to its guard window
  at 20:44:32Z. Handler returned in 0.71 s; checkpoint at step 912 written in 0.4 s (421bcc61...); process exit 75;
  driver released the lock 20:44:54Z; watchdog relaunched 20:45:52Z; training resumed from step 912 and logged step
  920 at 20:48:08Z. A full checkpoint fits inside Windows' shutdown window, so no lighter emergency format is needed.
Limits: nothing runs while the PC is off or logged out; the logon task resumes only after a login. A forced power cut
gives no message; the run then resumes from the last 50-step checkpoint. The driver started by the logon task stays in
the task's job (breakaway refused); the task has no time limit.
Not committed by the signer.

## 2026-10-14 (UTC), entry 55

FT3 verdict (MMBU lead session, Claude Opus 5.5), read by PREREG-FT3.md (entry 51) with amendments in entries 53 and
54. Chain finished 2026-10-14T07:12:05Z ("FT3 CHAIN DONE"). Bars file train/ft3/bars_ft3.json
8c418829143297f97bcdeec5b1815732444b1a6779a946bca3c258492cd456ae; held-out score file score_eval_heldout2_ft3.json
4d6074d8f7c78aad6f2c7c77a03302f80c01ce77f3bd9fe2c6bcdc78e9689935. Dev d09ff622, 3,102 rows, JP1.

G1 dev T_JP1 FT3Q_4B minus FT2_4B +0.0032 [-0.0093, 0.0158]: missed. G2 FT3Q_2B minus FT2r +0.0016 [-0.0110, 0.0142]:
missed. G3 adjusted S (JP1) FT3Q_4B minus FT3Q_2B +0.0343 [0.0232, 0.0453]: met (decision bar). G4 shell: FT3Q_4B Pass 2
0.9974 [0.9949, 0.9987], FT3Q_2B 0.9958: missed both. G5 FT3A_4B minus FT3Q_4B +0.0158 [0.0048, 0.0268]: met. G6
held-out answer FT3Q_4B minus Z4 +0.082 [0.058, 0.108]: met. G6 was read from the held-out score file; score_ft3.py
computed it but did not write it into its bars block (a scorer gap, mine; FT4's scorer writes it as a bar).

Triggers: (1) G3 met: the submission base is Qwen3.5-4B. (2) G1 and G2 both missed: Q1 breadth does not move dev
answers; G5 met, so per amendment 53 the submission-informing set is all tiers (author approval 2026-10-13). (3) G4
missed: the next row set adds Pass 2 rows with five and six requested fields. (4) G6 met.

Reported: FT3A_4B T_JP1 0.217 (T_em 0.141), C_strict 0.306; FT3Q_4B T_JP1 0.201, C 0.373 (all-tier rows lowered C by
0.067 against Q1-only rows; reported, not a bar). FT3Q_4B minus FT2r: T_JP1 +0.044 [0.029, 0.058].

Incident during FT3A_4B evaluation. At 05:57:29Z the driver raised PermissionError(13): its heartbeat os.replace hit
the heartbeat file while the watchdog had it open (race, mine). The driver's finally block released the lock while
its dev_context step (pid 5020) was still running; the watchdog relaunched the driver at 05:59:58Z (pid 36724; it was
the relaunch, not another agent) and at its next check exited on the "CHAIN: driver exception" line. The new driver
re-ran dev_context with the skip rule while pid 5020 still ran: FT3A_4B_context.jsonl holds 4,318 lines, 3,103 unique
ids, 1,215 duplicated, all duplicates byte-identical in raw_output, so no score changes (the scorer keeps one per id).
Fixes for FT4 (train/ft4/ft4_chain.py, ft4_watchdog.py): heartbeat writes retry and are never fatal; a driver exception
stops its step trees before the lock is released; driver exceptions are logged as retryable and relaunched (at most
6 in 6 hours); only a step failure is final.
Engine GPU turn: the engine agent's queued 5-minute RTX job ran 07:13Z to 07:18Z after "FT3 CHAIN DONE", released its
lock and removed its task. Not committed by the signer.

## 2026-10-14 (UTC), entry 56

FT4 preregistration (MMBU lead session, Claude Opus 5.5), before any FT4 GPU step. One arm, FT4_4B; bars H1 to H4.
Slice 4 build: slice4/BUILD-SLICE4.md 79b199e6... (record written by the lead after the build agent stopped; outputs
checked: 0 render failures, 0 dev-risk images in rows). Data disclosure regenerated: DATA-DISCLOSURE.md 703dcc87...,
disclosure/build_disclosure.py dccc39a1..., 79 sources.

| Record | SHA-256 |
|---|---|
| train/ft4/PREREG-FT4.md | fd798acb7ccb57da998f95e78fc64ed0268cbad7a5d6aa1adfe47195a35cc1d8 |
| train_rows_ft4.jsonl (29,421 rows) | 48ca93de69ade7b0bec819dbb477250928094bb84861be8738ce5316523de5ce |
| slice 4 train rows | c9dc10bcbab03e879d9120c45f82956b45a275b5ce9da7103a5a97f1ada4941c |
| build_rows_ft4.py; rows_ft4_report.json | a67d6428adc36a075fdce3c1aa470efa0758f4ab6c34fbe64997e7386916a192; 9d8c3cb25dd3f1edc2ed3887f654ab8d99caaae2ff8b9d369b847ae4c0c16981 |
| ft4_4b_config.json | 84f33808fccd0c362267c8c1401a460bc1218817796c451d3ff77857e8c6f6f3 |
| score_ft4.py (smoke-tested on the reference arms) | 983396762a4f20a1315349ab8d5983888e46abbb8a4fa9f1472b1152a9fefd1e |
| ft4_chain.py; ft4_watchdog.py; ft4_run.py | 9a26d959e78a87de8530758d316dbaaf86a9282367c6f5275a270d2800b3bc44; 015af6b54bd88fe1b1dacf1cceaad826575dc24e9db86c8f1532318e5d991b76; f6f4cb3a1ed8b2be02f13dbfe1c6461e73fed2a0ae4faa8fd32e349ed89583ed |
| train3.py; shutdown_guard.py (unchanged from entry 54) | f8e470680c45c0add1004ec052e376f5bbc72e755f991ac1de94075abad23fa5; 2e81cecaed775dd6da76c5290370b9b09cfb6b71faca6d79fcc14aad230ab0db |
Candidate labels in the prompt were considered and rejected under the harness rules (prereg section). Not committed
by the signer.

## 2026-10-14 (UTC), entry 57

FT4 sleep event, label-form rule set LF1, FT5 preregistration, sleep handling (MMBU lead session, Claude Opus 5.5).
CPU only; the GPU and the running FT4 processes were not touched.

FT4 event. System event 1074 at 13:28:39Z: shut down chosen from the Start menu ("power off"); Kernel-Power 42 entered
sleep 13:28:53Z; Power-Troubleshooter 1 resumed 18:35:50Z. The shutdown guard wrote a checkpoint at step 863 (not a
50-step boundary; checkpoint e5ec3279...); its "shutdown-save" log line is missing because train3.py released the
handler (G.done()) before writing the log line and Windows ended the process. The FT4 watchdog relaunched the driver at
18:36:21Z; training resumed from step 863 at 18:37:12Z, one trainer. Fix for later runs: log first, then release
(train/ft5/train3.py). The running FT4 trainer keeps the old order.

LF1 (train/labelform/): labelform.py f2bfae29..., test_labelform.py d219ce50..., rules lf1_rules.json fc4c6bb8...,
alternates 7c854b06.... Rules derived only from stored source documentation; an audit hook refuses any dev file;
test: build completes twice with identical outputs, the hook refuses a deliberate dev read (control), every accepted
quote contains its alternate. 5 of 19 documentation rules accepted (CRIC abbreviations), 14 UNSOURCED. Coverage count
(measure_lf1.py 20c7b28a..., lf1_coverage.json 9c8fe7c6..., a separate dev read that changes nothing): 558 -> 563 of
2,677 classification-type dev golds.

FT5 preregistration: train/ft5/PREREG-FT5.md 171dc34ff0f80963cd8fcd29fdad126cb62cf071da971c175f90d669880717be. Second
epoch from the parent adapter chosen by rule P1 on FT4's H1 (ft5_select.py 6c32a14a...); LF1 rows and the combined arm
rejected with numbers. Bars K1 (dev T_JP1 > parent), K2 (held-out non-inferiority, margin 0.02), K3 (shell). Scorer
score_ft5.py 6526de97... (smoke-tested with a temporary parent file, removed). Code: train3.py e61a2ef5... (init_lora,
log-first shutdown save), ft5_chain.py 8c1d34e8..., ft5_run.py 3651be92..., ft5_watchdog.py dc17c290...,
shutdown_guard.py unchanged 2e81ceca....

Sleep handling: ft5_watchdog.py and ft4/ft4_watchdog.py (f5cd3de5..., used at FT4's next logon start; the running FT4
watchdog keeps its loaded version) detect a resume by a loop gap over 3 minutes and by Kernel-Power 107 or
Power-Troubleshooter 1 System events, log them beside the checks, and give a live driver 10 minutes of grace before a
stale heartbeat counts as hung. Survival note updated: LONG-JOB-SURVIVAL-NOTE-2026-10-13.md 8396099d....
Not committed by the signer.

## 2026-10-14 (UTC), entry 58

Organizer notes, submission package, overlap check, FT5 amendments 1 and 2, baselines, perception audit, COSEM and
REAL_COLON, fast kernels (MMBU lead session, Claude Opus 5.5). CPU only; the FT4 run and its environment untouched.

Source: ORGANIZER-NOTES-DISCORD-2026-10-14.md 1aba95fbcc3b01d00a5655b9709797547ae92666e3af528ad5835773e00fb0ce
(organizer statements relayed by the author; guidance, not the written rules).

1. Submission package (rehearsal, nothing uploaded): submission/package.py b081280d... built
   E:/mmbu-submission-rehearsal/ft3a_4b (FT3A_4B merged, bf16, no MTP tensors; chat template default non-thinking,
   one line changed from the base; generation_config greedy, 768 tokens, stops <|im_end|> <|endoftext|>).
   check_package.py 5645e9d1... static: 6,206 dev prompts (both passes) render byte-identical under plain defaults to
   the runners' enable_thinking=False render (0 differ); the base template's default opens a thinking block
   (risk confirmed); checkpoint 4,539,265,536 parameters, 0 MTP (log 20fda640...). GPU check with plain
   model.generate defaults is queued after FT4.
2. Public split evaluation-only check: diag/public_overlap_check.py 3d7158a2..., result 37dc0b39.... FT4 rows (29,421
   rows, 15,909 images) against the three dev revisions: 0 exact image copies, 0 exact question matches, 5,368
   pHash candidates, 10 confirmed and 11 at-risk pairs, all BBBC010 training images (43 rows) against dev images.
   These BBBC010 rows were also in FT2, FT3 and FT4 training (Q2 source, quarantine gap, mine). Amendment 2: FT5 drops
   the 11 images from its rows; 12 dev rows are excluded from FT5 comparisons (diag/excluded_dev_rows.json 665f3f3f...).
   FT4's bars are read as preregistered and reported again without those rows.
3. FT5 amendment 1 (train/ft5/PREREG-FT5-AMENDMENT-1.md 684e83c0...): all-tier 2B arm FT5_2B on the same rows as the
   4B parent, run first; bar B2 (adjusted S on JP1, 4B parent minus FT5_2B) with ties and reverse triggers.
   ft5_select.py af9b80ba..., score_ft5.py c5504547..., ft5_chain.py c05cc43f....
4. Parameter counts from safetensors headers: Qwen3.5-4B 4,659,865,088 in the hub checkpoint (MTP 120,599,552; vision
   333,514,240; embeddings 635,699,200), 4,539,265,536 without MTP; Qwen3.5-2B 2,274,069,824 and 2,213,241,664.
   Multipliers (4.66e9 / P)^0.1: 4B 1.0000 or 1.0026; 2B 1.0743 or 1.0773.
5. Track plan TRACK-PLAN-2026-10-14.md abcb04ae...; organizer question draft DISCORD-QUESTIONS-2026-10-14.txt
   964556f4... (not sent).
6. Baselines (diag/baselines.py d6141c52..., baselines.json d135ae4f...), dev d09ff622 minus 12 rows, JP1: chance among
   the judge's options 0.207; leave-one-out label prior (oracle) 0.237; zero-shot 2B 0.168, 4B 0.185. Best FT so far
   (FT3A_4B) 0.217. A physician baseline is UNAVAILABLE.
7. Image-perception audit preregistered in diag/image_audit.py 26782170... (A1 answer change rate, A2 real minus blank
   images; trigger: A2 lower bound at most 0.01 sends the next run to vision-side LoRA). Queued in
   train/post_ft4_queue.py 5479b1b9... (MMBU-POSTFT4 logon task: waits for "FT4 CHAIN DONE", then fast-kernel test,
   package GPU check, audit, then FT5).
8. COSEM reader slice5/cosem/cosem_reader.py 2cae6f48...: blosc-lz4 and zstd zarr via numcodecs 0.17.0 (build venv),
   local copy plus public bucket chunks (cached with SHA-256); codec parity local vs bucket: equal. The id rule
   "position + 1" fails past id 33 (tested); ids are mapped per crop by exact chunk equality with per-class arrays;
   unmatched ids are dropped. Sections at 8 nm extracting (resume by skip).
9. REAL_COLON: 46 of 60 videos have lesion boxes (rc_boxed.json 650ae92b..., figshare list rc_files.json d9aa088a...).
   Downloaded and MD5-verified 001-005 (6,611,028,228 B, 6af1c186...) and 002-002 (8,160,079,731 B, cab0f489...);
   it joins the next row set. MATEK_BM_TCIA held: TCIA's route needs the IBM Aspera Connect install and its licence
   acceptance, a terms acceptance for the author.
10. Fast kernels in a copy (E:/venvs/mmbu-fastk; D:/venvs/mmbu untouched): triton-windows 3.7.1.post27 (MIT),
    flash-linear-attention 0.5.2 and fla-core 0.5.2 (MIT). transformers 5.18.0 now resolves chunk and recurrent gated
    delta rule to fla in the copy and to torch in the original (checked by closure). causal-conv1d 1.7.0 ships only an
    sdist needing nvcc; no CUDA toolkit is installed, so it stays on the torch path. GPU parity and speed test
    slice5/fastk/fastk_gpu_test.py af7d2ade... (bars in its header) runs under fastk_locked.py e43a67e5....
Not committed by the signer.
Addendum to entry 58, same session minutes later: train/post_ft4_queue.py is now
26e36e5f8de7f865bc19f2a19e8777b978341d60529feeae5198fd2bcb86e293 (adds the FT4 re-read without the 12 overlap rows,
train/ft4/score_ft4_excl12.py c9b23e17ee4a8ac2cdf1e40d4ed6e46b207e10566dbbfe8149bac71fe58cc2c6, reported only; FT4's
bars stay as preregistered). The queue process was restarted to load it; it had only been waiting.

## 2026-10-14 (UTC), entry 59

Organizer answers and MATEK (MMBU lead session, Claude Opus 5.5). CPU only; FT4 untouched.

Organizer answers (email from Ryan D'Cunha, 2026-10-14 20:22Z, logged in mission-control/2026-10-14-mmbu-outreach/
PROGRESS.md, relayed verbatim by the coordinator): "Field names cover both spelling and fields are always listed in
order. Only annotated fields are requested (an X-ray won't ask for stain type. Unknown would be counted as incorrect.
Generation settings are the uploaded chat template and json from hugging face. The whole reply does not need to parse
as JSON. In pass 1, the harness won't defaulted to raw reply it must be a json format. The prompts in the brief and
hugging face are the latest up to date". Effects: (1) the package approach is confirmed (our uploaded template and
generation_config are used). (2) scoring/score_v3.py d7b25f62... aligns local reading (Pass 1 JSON answer required, no
raw fallback; Pass 2 JSON object may sit inside the reply; unknown scores 0); diag/score_v3_all.py fbbbc7ba..., result
89e64ad5...: under v3, FT3A_4B T_JP1 0.2161, C 0.3077, Pass 1 JSON found 3,089 of 3,091, quoted "unknown" values 3;
FT3Q_4B 15; FT2_4B 5; zero-shot Z4 2,132. Reported variant; bars keep their scorers. (3) "unknown": training rows hold
none; the package generation_config now blocks the token unknown right after an opening JSON quote (bad_words_ids;
submission/package.py 7424fb20...); check_package.py 62b93132... measures it on every row where the runner emitted it.
(4) FT5 amendment 3 (train/ft5/PREREG-FT5-AMENDMENT-2-3.md 85ece906..., score_ft5.py dc9e5fcb...): bar K4, a Pass 1
JSON answer on every scored dev row, per FT5 arm. (5) The post-FT4 queue (train/post_ft4_queue.py e5746a0a...) now
re-reads FT4 under v3, packages the FT4_4B candidate and runs the GPU package check on it.

MATEK_BM_TCIA: the author installed IBM Aspera Connect and accepted its licence (2026-10-14, verbatim "We installed
Aspera already, and accepted."). slice5/matek/matek_fetch.py 2c0be014... uses the public link's own OAuth flow
(authorize_public_link, token endpoint) and obtains the package's transfer spec; no account, no form. Headless ascp
(Connect 4.2.15, ascp 4.4.3) fails token authentication without the token-auth SSH key, and Connect's key file is
passphrase-encrypted; it was not decrypted or worked around. Not downloaded. Routes: the author starts the package
download in the browser through Connect, choosing E:\datasets\mmbu-matek, or an R&D install of IBM's aspera-cli,
which ships IBM's published token-auth key. TCIA's annotation manifest (annotations.dat zip, 33,201 B, 4db78414...) is
stored for verification. Not committed by the signer.

## 2026-10-14 (UTC), entry 60

MATEK_BM_TCIA downloaded and verified (MMBU lead session, Claude Opus 5.5), by the IBM command-line route the
coordinator relayed, under the author's words of 2026-10-12, verbatim: "yes, you may install dependencies that will
help. Ideally, we ship without any dependencies, and build our own infrastructure in R&D, to minimize reliance on
outside sources." and his 2026-10-14 Aspera install and licence acceptance ("We installed Aspera already, and
accepted."). R&D tooling only; nothing ships with it. Installed for the current user, no PATH change: RubyInstaller
4.0.7-1 x64 (rubyinstaller-4.0.7-1-x64.exe 552911af..., equal to the release's published digest) at C:\Ruby40-x64;
aspera-cli 4.27.5 (Apache-2.0, rubygems sha 85c39578...); IBM Aspera Transfer SDK 1.1.9 (ascp 4.4.8.2592) installed
by `ascli config ascp install` into C:/Users/Zain/.aspera/sdk with IBM's published token-auth keys
(aspera_bypass_rsa.pem, aspera_bypass_dsa.pem). Connect's passphrase-encrypted key was not used, read or decrypted.
Download: `ascli faspex5 packages receive --url=<TCIA public link>` (slice5/matek/matek_ascli.ps1 1ee86f95...) into
E:\datasets\mmbu-matek, package 735 status success, 0 partial files left, about 12 GB on disk. Verification
(slice5/matek/verify_matek.py d52fac0e..., result verify_matek.json 125ce07f...): TCIA's annotation list (18,365
images), the package MD5 list (AML-Cytomorphology.sums dd7a17eb..., 18,365 entries) and the files on disk agree
exactly; 0 missing, 0 MD5 mismatches, 0 extra. Rows for MATEK, REAL_COLON (two videos) and COSEM (64 sections) are
being built by a slice 5 build agent (CPU, BelowNormal, outputs on E:), with quarantine against both dev revisions and
the disclosure regenerated. FT4 and the POSTFT4 queue were not touched. Not committed by the signer.

## 2026-10-14 (UTC), entry 61

Slice 5 rulings and the bone-marrow Matek collection (MMBU lead session, Claude Opus 5.5), on the coordinator's
rulings of 2026-10-14. CPU and network only; FT4 and the POSTFT4 queue untouched.

1. Collection: the MMBU paper (sources/paper.txt, page 5) names "Bone-Marrow-Cytomorphology: An expert-annotated
   dataset of bone marrow cytology in hematologic malignancies" with a bone marrow smear example question, so the
   MMBU source is TCIA Bone-Marrow-Cytomorphology_MLL_Helmholtz_Fraunhofer (package 601, CC BY 4.0, 945 subjects,
   171,374 images per its MD5 list). The package already on disk (735) is AML-Cytomorphology_LMU (peripheral blood).
2. Tiers by the slice 3 procedure with terms from each collection's own description, written before the read
   (slice5/tiering/tier_search.py abc81556...; results d09ff622 bc0be7df..., 94126985 457d4903...; reads logged):
   AML_LMU Q2 ("peripheral blood smear", 29 dev rows; a term shared with other blood-smear sources), MATEK_BM_TCIA
   Q2 ("bone marrow", 42 rows). Under the author's 2026-10-13 approval both may enter training; the AML_LMU rows
   (slice 5, built under slice 1's id) stay, disclosed with tier Q2 and licence CC BY 3.0 as found.
3. Disclosure regenerated (disclosure/build_disclosure.py dab8f4fd..., DATA-DISCLOSURE.md 0fb0cbe9..., 82 sources).
   BUILD-SLICE5.md (93ee3459...) records the rulings, including the accepted read-only abbreviations.txt fetch
   (541 bytes, hash in mmbu-slice5-build/docs/host/index.json).
4. Bone-marrow download started 22:15Z by the same aspera-cli route into E:\datasets\mmbu-matek-bm
   (slice5/matek/matek_bm_ascli.ps1 b76b9811...), BelowNormal, logon task MMBU-MATEKBM-resume reruns it after a
   restart and removes itself on success; verification against the package MD5 list (verify_matek_bm.py 7a535224...)
   runs at the end. About 6,000 files in the first 10 minutes, so about 5 hours in total (inferred). Its rows are built
   after verification as their own source; slice 5 rows join the next training set only through the existing
   quarantine. Not committed by the signer.

## 2026-10-15 (UTC), entry 62

FT4 verdict and post-FT4 results (MMBU lead session, Claude Opus 5.5). FT4 chain done 00:41Z; queue done 01:29Z.

FT4 read by PREREG-FT4.md (bars_ft4.json 82f8c2ca...), dev d09ff622, JP1: H1 dev T FT4_4B minus FT3A_4B -0.0074
[-0.0184, 0.0039]: missed. H2 dev shell Pass 1 1.000, Pass 2 0.9997 [0.9982, 0.9999]: met. H3 dev C +0.0314
[0.0276, 0.0352]: met. H4 held-out answer FT4_4B minus Z4 +0.111 [0.083, 0.141]: met. Triggers: (2) H1 missed: MMBU's
own sources do not move dev answers at this scale; the next levers are label form, a second epoch, and the rationale
route (gated). Rule P1 sends FT5 to parent FT3A_4B. Reported: T_em -0.0145 [-0.0229, -0.0061]; adjusted S +0.0004
[-0.0085, 0.0094]; held-out answer FT4_4B minus FT3A_4B +0.023 [0.007, 0.041]. Re-read without the 12 overlap rows
(bars_ft4_excl12.json ca54d77a...): same verdicts. Under score_v3 (score_v3_all.json d242745d...): FT4_4B T 0.2087,
C 0.3384, Pass 1 JSON found 3,091 of 3,091, quoted unknown 1.

Fast kernels (fastk_compare.json 2d428f43...): parity passes (48 of 48 replies identical; first-step logits max 0.219;
op parity fp32 max 0.0014, bf16 0.0039); speed fails: generation 0.30x and training 0.33x of the reference on this
short test, which includes Triton's first-run compile (inferred cause). The fast environment is not used for scored
runs; a longer warm test is needed before any decision.

Package GPU check (check_gpu_FT4_4B.json 35aa6193...), plain transformers defaults: 48 of 48 Pass 1 replies score the
same as the runner (47 identical after whitespace; the runner keeps a trailing newline), 48 of 48 strict, no thinking
tag; Pass 2 on the 1 runner reply with "unknown" plus 48 rows: 0 unknown after blocking, context sum 5.0 both.

Image-perception audit (image_audit.json 6944a2c1...): T_JP1 real 0.2087, blank 0.0819; answer change rate 0.747;
A2 real minus blank +0.127 [0.113, 0.141]; trigger not met: the model does read the image.

FT5 started 01:29:57Z (parent.json 334c06d7...: parent FT3A_4B, rows train_rows_ft5b.jsonl d9460184..., 22,992 rows:
FT3A rows minus the 11 overlap images plus the format copies). Arm FT5_2B first; logon task MMBU-FT5-resume. Not
committed by the signer.

## 2026-10-15 (UTC), entry 63

Prior-gap analysis (MMBU lead session, Claude Opus 5.5), CPU only on saved outputs; FT5 and the GPU untouched.
Readout fixed before the run: diag/prior_gap_prereg.md 4a3d6dd3...; result diag/prior_gap.json fcf37e9b....
Same rows and scorer: baselines.py and score_v3_all.py both use dev d09ff622 minus the 12 excluded rows (3,091) and
JP1; the models are read under score_v3 (no raw fallback). Both baselines use information the model never has: the
chance figure picks among the judge's options, and the label prior reads dev answers of other rows (an oracle).
Findings, FT4_4B (FT3A_4B in brackets): the model beats the prior on classification 0.204 (0.188) against 0.168,
counting 0.580 (0.623) against 0.522, and detection 0.073 (0.069) against 0; it loses on from-segmentation 0.172
(0.224) against 0.426 and from-detection 0.149 (0.201) against 0.295. 51% of answers name no option. The model is
right where the prior is wrong on 13.7% of rows, and the reverse on 16.5%. Oracle ceiling: replacing only the
off-taxonomy answers with the leave-one-out prior would give 0.314 (0.319); with a training-derived prior, 0.235
(0.241), because training answers rarely match dev label words (that prior alone scores 0.064). Largest family gaps:
the chest radiograph region family (82 rows, model 2 against prior 40) and surgical instrument tips (54 rows, 7
against 31). Saved outputs hold text only, so prior-aware decoding on option scores is not testable on them;
diag/option_scores.py c7bc0a90... (eval-only, teacher-forced option log-probabilities, readout R1 and R2 written in
its header, blend weight fitted on training-source selection rows, never on dev) is proposed for after FT5. Not
committed by the signer.

## 2026-10-15 (UTC), entry 64

Option-scoring readout rule fixed before any run, its queue, and the two candidate row sets (MMBU lead session,
Claude Opus 5.5). FT5 and the GPU untouched.

diag/option_scores.py b4c042f4536c4a622f16c56ddf97d15affb2089ec40b616ed22f88069463ccee: eval-only teacher-forced option
scoring of FT5_4B on dev d09ff622 region and classification rows (12 excluded rows dropped). Rule in its header: R1
option-rank accuracy against G, the same arm's generated-answer JP1 on the same single-label rows; if R1 minus G is at
least 0.05 with a paired bootstrap lower bound above 0 (seed 20261002, 10,000 resamples), the next row set is (a)
answer-vocabulary rows; otherwise (b) extra region rows. R2 (prior blend) dropped: selection rows carry no option
sets, and nothing is fitted on dev. Queue train/post_ft5_queue.py 419abf2e... (logon task MMBU-POSTFT5, started
02:07Z): waits for "FT5 CHAIN DONE" (written after FT5 scoring), runs the scoring under the GPU lock (about 40
minutes), then the readout, then removes itself. A slice 6 build agent (CPU, BelowNormal, outputs on E:) is building
both sets now: (a) train_rows_s6a_vocab.jsonl (every class of each existing region source's published label set) and
(b) train_rows_s6b_region.jsonl (open chest radiograph region and surgical instrument part sources), with the same
quarantine against both dev revisions and the disclosure updated. Not committed by the signer.

## 2026-10-15 (UTC), entry 65

Coordinator rulings on slice 6 (slice6/BUILD-SLICE6.md), relayed 2026-10-15, applied by the slice 6 build agent at the
lead session's instruction (MMBU lead session, Claude Opus 5.5). (1) Set (a) may reuse images that earlier slices
placed in their train split, to fill the missing CRIC (Squamous cell carcinoma), DeepBacs (Rod, Dividing,
Microcolony) and DRAC classes; reused images stay in train only, the dev near-duplicate quarantine applies, and reuse
is recorded per row (rule R-S6A-REUSE-TRAIN-v1). (2) ChestX-Det is treated as an MMBU source (tier Q2, from 5 images
in confirmed dev near-duplicate pairs, all dropped); the disclosure states that its renamed files could not be
checked against the NIH ChestX-ray14 official test list, so NIH test images may be present. (3) Zenodo: the build's
helper had sent two 16-byte range probes (SurgPose, NODE21) with a browser-style user agent after Zenodo refused curl's
default; no data was downloaded with it. Ruling: an honest descriptive agent only (tool name plus the public project
URL, no personal email); if Zenodo still refuses, the source is recorded as blocked, with no workaround. The rebuilt
set (a) hashes and the Zenodo outcome are recorded in a later entry. FT5 and the GPU untouched. Not committed by the
signer.
Addendum to entry 65 (same session, after the rebuild): set (a) E:/datasets/mmbu-slice6-build/train6/a_run1/
train_rows_s6a_vocab.jsonl 088dc309fc9ebd368fb80c8d0b1fabc0542efe6f57eb73c66bd4774984471075 (2,412 rows; 434 rows on
reused earlier-train images: CRIC 170, DeepBacs 204, DRAC 60, all split train, rule R-S6A-REUSE-TRAIN-v1, checked by
the lead); set (b) train_rows_s6b_region.jsonl 846405265c0a7948a9357d4a4837908fe62ed7b4057b30f5fec4ace08118be3d (386
rows, ChestX-Det tier Q2, slice6/tiering/tier_rulings.json c8cc9cd3...). Both twice-built identical (a third build
with the stored-document set fixed matches run2 on all 17 outputs). Zenodo with the honest agent
"mmbu-slice-builder/1.0 (+https://harperz9.github.io)": SurgPose and NODE21 metadata HTTP 200 and 16-byte range HTTP
206; neither blocked, neither downloaded or built. DATA-DISCLOSURE.md 67f5b167... (84 sources, ChestX-Det at Q2 with the
NIH test-list note); slice6/BUILD-SLICE6.md 4e841124.... Hashes recomputed by the lead.

## 2026-10-15 (UTC), entry 66

FT5_4B crash fix on record, bone-marrow verification and slice 7, and the FT6 preregistration (MMBU lead session,
Claude Opus 5.5). Written 20:50Z while FT5_4B's dev context pass runs: before train/ft5/bars_ft5.json and
diag/option_readout_FT5_4B.json exist, and before any FT6 GPU step. CPU only; FT5 and the GPU untouched.

1. FT5_4B crash fix (coordinator, 15:45Z, STATUS-2026-10-15.md): train/ft5/train3.py was e61a2ef5... at entry 57;
   the init_lora log call passed path= into train2.log, whose first parameter is path (TypeError, crashes 05:34Z and
   14:36Z). The keyword is now init_path; train3.py 3f803f1ab66ddb0b567803d8841c24c3dee49aff9ca6be5e7c810f1b0b77ad07.
   No change to training logic, data, config or prereg. Relaunched 15:39Z; training ended 19:39:52Z rc 0. Cost about
   10 h of GPU idle. Lesson: an untested branch ran first inside a multi-hour chain; FT6 adds a dry run (item 4).
2. Bone-marrow MATEK_BM_TCIA (package 601): ascli exit 0; a rerun at 14:34Z skipped all 171,375 transfers.
   verify_matek_bm.json 043548ce...: 171,374 listed, 171,374 on disk, 171,373 JPGs match their MD5, 1 missing
   (.PMO_10000.jpg.asp-trapd-lnk, listed with the empty-file MD5, an Aspera placeholder name, inferred) and 1 extra
   (PMO_10000.jpg, 41,461 B, no reference MD5). Strict pass is false. Lead ruling R-S7-VERIFIED-ONLY-v1: only the
   171,373 verified images enter the pool; PMO_10000.jpg is excluded. Defect: matek_bm_ascli.ps1 writes
   bm_download.done and removes its logon task whatever the verification says (recorded, not changed; the task is gone).
3. Slice 7 (build agent, CPU): E:/datasets/mmbu-slice7-build/train7/run1/train_rows_s7.jsonl
   02abedfd16c1d67a31cd2d0e072c0fd2702b5d198e4a92109b6d0ae391b74375, 920 rows (460 classification, 460 context), 20
   classes with names quoted from the stored TCIA page (slice5/bm_page.html), stain "May-Grünwald-Giemsa", run1 equals
   run2. Lead rulings: NIF ("Not identifiable") dropped (R-S7-NO-NIF-v1, an unknown-style answer); the stain substring
   accepted. Quarantine: 4 confirmed dev pairs (FGC_00019, KSC_00040 copies in both revisions) dropped; slices 1 to 6
   and AML_LMU candidates all rejected at stage 2. BUILD-SLICE7.md aed48b9f..., licences_slice7.json 1f890c7f... (CC BY
   4.0). DATA-DISCLOSURE.md fb54d618... (85 sources). Tier Q2.
4. FT6 preregistration: train/ft6/PREREG-FT6.md 42669b8ab0a816282ca77a2980ec19bf73a600c43b46d09749288e2c1d0f1934.
   Rows: FT5 rows + the slice 6 set the option readout names + slice 5 + slice 7 (inputs pinned in ft6_inputs.json
   a6af8d21...). Rule P2 (ft6_p2.py 28140b9e...) sets C4 and the arms from bars_ft5.json. FT6_4B on FT5_4B's start and
   recipe; FT6_2B only if B2 was missed. Bars M1 to M7 and B3 (score_ft6.py 5830de49..., smoke test pending; any later
   change is recorded with its reason). Code: build_rows_ft6.py 8ebfc6e4..., train4.py 4274c0b0... (train3.py plus two
   dry-run-only keys), ft6_run.py 315c9d02..., ft6_chain.py 6b68b5ef..., ft6_watchdog.py b67381a6... (removes its
   task at done), ft6_dryrun.py ddcf0549..., shutdown_guard.py unchanged 2e81ceca.... Reported variant for FT5:
   train/ft5/score_ft5_v3.py 0ee9d406... (organizer rules; the bars keep score_ft5.py). Not committed by the signer.

## 2026-10-15 (UTC), entry 67

FT5 verdict, the failed option-scoring run and its rerun, FT6 amendment 1 and rule P2 (MMBU lead session, Claude
Opus 5.5). FT5 chain done 21:36:51Z.

1. FT5 read by PREREG-FT5.md and amendments (bars_ft5.json b367b970..., score_ft5.py as in entry 59), dev d09ff622
   minus 12 rows, JP1, paired bootstrap: K1 dev T FT5_4B minus FT3A_4B +0.0010 [-0.0071, 0.0091]: missed. K2 held-out
   answer FT5_4B minus FT3A_4B +0.0116 [-0.0016, 0.0252] (score_eval_heldout2_ft5.json 0d4bb17b...): met. K3 shell
   FT5_4B Pass 1 0.9997 [0.9982, 0.9999], Pass 2 0.9974 [0.9949, 0.9987]: missed (8 Pass 2 rows, each the brace
   defect on the five-field no-stain set). K4 Pass 1 JSON found FT5_4B 3,090 of 3,091 (54d3c99568f9), FT5_2B 3,089
   (54d3c99568f9, b5b36b202ea0): missed (each a detection box list cut at 768 tokens). B2 adjS FT3A_4B minus FT5_2B
   +0.0440 [0.0329, 0.0554]: met (with-MTP counts +0.0439 [0.0329, 0.0552]). Variant under score_v3
   (train/ft5/score_ft5_v3.py 0ee9d406..., bars_ft5_v3.json 1025944a...): K1 +0.0010 [-0.0071, 0.0091], K4 the same
   counts, B2 +0.0440 [0.0329, 0.0554]; Pass 2 JSON found 3,091 of 3,091 for FT5_4B. Triggers: K1 missed: epochs are
   not the lever; next the gated sources (MATEK bone marrow now built), Pass 2 rows for the dev field sets (K3), the
   rationale route (closed). B2 met: the base stays 4B. The candidate stays FT3A_4B. Reported: FT5_4B minus FT3A_4B
   C +0.0086 [0.0062, 0.0112], adjS +0.0025 [-0.0040, 0.0090], T_em 0.0000 [-0.0068, 0.0068].
2. Option scoring, FT5_4B: the POSTFT5 run crashed on its first row at 21:37Z (IndexError in Qwen3.5 get_rope_index:
   the processor's mm_token_type_ids kept the prompt length while input_ids grew by the continuation). The queue then
   ran the readout over 0 rows, which printed next_row_set "b" from NaN values. That readout is void, kept as
   diag/option_readout_FT5_4B.INVALID-empty-run.json 9cd2c8ea...; the empty score file and the rc-1 marker are kept
   with INVALID names. Fix, code only, rule text unchanged: diag/option_scores.py
   6b70b2f3a1f852c830177fb743c9719c414759890c220fea77e597ba0acb4008 (continuation tokens get type 0; --limit and
   --out for a dry run; the readout refuses unless all 2,665 rows are scored). Rerun queue train/post_ft5_queue2.py
   29f39f2f... (logon task MMBU-POSTFT5 re-registered 21:40Z): a 3-row dry run under the lock, then the full pass,
   then the readout. Same lesson as FT5: this script had never run before its queued pass.
3. FT6 amendment 1 (train/ft6/PREREG-FT6-AMENDMENT-1.md 7859687c..., before any FT6 GPU step): K4 response, one extra
   copy of each training detection row with at least 10 boxes (#det10). K3 response considered and rejected for FT6:
   dev field-set count (structure only, no values): 2,503 of 3,103 rows ask body part, modality, submodality,
   specimen, medical domain, a set with 0 training rows; the only training rows holding specimen and medical domain
   are 400 PBC rows with one identical value set, so derived rows would teach one blood-smear answer; it needs a
   label build. build_rows_ft6.py 10c8d9d6....
4. Rule P2 (ft6_p2.py as entry 66): C4 FT3A_4B, arms [ft6_4b] (B2 met), ft6_arms.json 0f13b307..., ft6_4b_config.json
   d0c945ea... (FT5_4B's recipe, FT6 rows). Not committed by the signer.
Addendum to entry 67 (22:00Z): the submission candidate stays FT3A_4B by PREREG-FT5's triggers. It was repackaged
with the current submission/package.py 7424fb20... (adds the "unknown" bad_words_ids block) into
E:/mmbu-submission-rehearsal/ft3a_4b_v2 (4,539,265,536 parameters, 200 LoRA layers merged); check_package.py static
pass. The GPU package check of this folder is pending (queued for the next GPU gap). Option-scoring dry run: 3 rows,
rc 0, 51 s; full pass started 21:48:43Z at about 1 row per second.

## 2026-10-15 (UTC), entry 68

Option-scoring readout, the FT6 rows, the dry run and the FT6 queue (MMBU lead session, Claude Opus 5.5).

1. Option scoring FT5_4B (option_scores.py as entry 67): 2,665 rows scored, rc 0, 2,601 s (21:48:43Z to 22:32:04Z);
   option_scores_FT5_4B.jsonl f7c6a4c0.... Readout by the rule fixed in entry 64 (option_readout_FT5_4B.json
   6aca9076...): 2,654 single-label rows, R1 0.4137, G 0.1967, R1 minus G +0.217 [0.198, 0.236]; multi-label rows 11,
   top-k set accuracy 0.0. Rule: at least 0.05 with lower bound above 0, so the next row set is (a), answer vocabulary.
   Reading: the model ranks the gold option first on 41% of these rows but says it on 20%; the gap is wording and
   label-space recall, not perception alone (inferred; teacher forcing over closed options is easier than open
   generation).
2. FT6 rows (build_rows_ft6.py 10c8d9d6...): D:/datasets/discernment/ft6/train_rows_ft6.jsonl
   17f2c2c663a6045e38c9f1cc604bf9f740b0a3c1979af8ca5465bec1637d7d2b, 27,785 rows (16,673 task, 11,112 context),
   65 sources: FT5 rows 22,992 + slice 6 set (a) 2,412 + slice 5 1,384 + slice 7 920 + 77 detection copies
   (amendment 1). Checks passed: no repeated row_id, all trainable, all images present, no overlap image.
   rows_ft6_report.json 3a938128....
3. Dry run (ft6_dryrun.py ddcf0549..., result ft6_dryrun.json c0d831f9...) under the lock 22:42:08Z to 22:47:15Z:
   arm ft6_4b with its real config, 112 rows (one per source and pass): train with init_lora (2 steps), train again
   from the step-2 checkpoint (resume logged, 7 steps), dev task and context 6 rows each, held-out 6 rows; every step
   rc 0; all_pass true. score_ft6.py smoke-tested on CPU with stand-in outputs (FT4_4B as FT6_4B, FT5_2B as FT6_2B):
   every bar computed; its M3 and M4 match FT4's entry 62 figures for the same pair.
4. Queued: logon task MMBU-FT6-resume registered and started 22:47:37Z (pythonw ft6_watchdog.py, IgnoreNew, hidden);
   the driver waits for the lock behind the FT3A_4B v2 package GPU check (train/ft6/locked_run.py 883f5150...).
   About 1,736 optimizer steps at about 10 s each (inferred), then dev, held-out and scoring. Stop: train/ft6/FT6.stop.
   Not committed by the signer.
Addendum to entry 68 (22:55Z): FT3A_4B v2 package GPU check (check_package.py gpu, plain transformers defaults,
submission/check_gpu_ft3a_v2.log) rc 0: 48 of 48 Pass 1 replies score the same as the runner (0 byte-identical;
the runner's replies differ in whitespace, as at entry 62), 48 strict, no thinking tag; Pass 2: 3 runner rows with
"unknown", 0 after the block, C sum 5.4 both. FT6_4B training started 22:51:47Z (init_lora logged, sha 9943cdd0...);
step 10 of 1,736 at 22:53:58Z, loss 0.192, about 9 s per step. The dry run's checkpoint.pt was deleted (D: space);
its logs and adapter stay in D:/datasets/discernment/ft6_dry.

## 2026-10-15 (UTC), entry 69

Coordinator follow-ups while FT6 trains (MMBU lead session, Claude Opus 5.5). CPU only; FT6 and the GPU untouched.

1. Slice 8 plan slice8/PLAN-SLICE8.md 8004c685300cfb486973521306bebd9ec3aaa019eb49e36861280baa4efea635 and FT7
   preregistration train/ft7/PREREG-FT7.md aaf802461241335966358268ce217253be385ed9e35eaede70c3fa27fbeb68f1, both
   written before any slice 8 row is built. Survey (dev field presence and task strings only, no dev values): every
   dev row asks specimen and medical domain; field sets S1 2,503, S2 292, S3 278, S4 30; training holds 0 rows for
   S1, S3, S4. The MMBU paper's worked example (sources/paper.txt p. 5) gives "Metadata_specimen: Human"; training's
   specimen values are preparation types (Blood Smear 802, Tissue Section 800, FFPE Tissue Section 356, bone marrow
   460, plus C. elegans 218 and blastocyst 24); medical domain only Hematology 400, Ophthalmology 399,
   Gastroenterology 197. FT7 bars N1 to N6 (C first; T non-inferiority 0.01).
2. Disk (D:, 15,338,897,408 B free at 22:58Z): FT6 keeps one checkpoint.pt, rewritten every 50 steps through a
   .tmp file then os.replace, so peak use is two checkpoints during a write (2 x 366,172,859 B, the size measured on
   FT5 and on the FT6 dry run) plus lora_state.pt (122,031,841 B) and logs: about 0.86 GB. Dev and held-out outputs
   go to C:. Peak cannot exceed free space; no file was moved.
3. slice5/matek/matek_bm_ascli.ps1 is now 3acd891f60756c77c1cf698a62c97acb3c3b3c5ebdd5b28e895f5a8fe74dfc0a: it writes
   bm_download.done and removes its logon task only when verify_matek_bm.json has "pass": true; otherwise it writes
   bm_verify.failed and keeps the task (parse check: 0 errors). The marker written on the failed verification of
   2026-10-15 is renamed bm_download.done.WRITTEN-ON-FAILED-VERIFY (no task exists, so nothing reruns).
Not committed by the signer.
Addendum to entry 69 (23:01Z, before any slice 8 row): FT7 code train/ft7/score_ft7.py
1ffc02fdb939a5a19adbe0dc69bb9815cd6e58bfdf9d7fdd12a1821d0f37edfe (smoke-tested on CPU with stand-ins FT5_4B as FT7_4B
and FT4_4B as FT6_4B: every bar computed; N4 and N5 equal FT5's adjS and K2 figures for the same pair; S1 rows 2,502
after the 12 exclusions) and rule P3 train/ft7/ft7_p3.py 444e0ad1f52d1b0f924c96ca8852c5c9dd26aa912a7a75a51698fbc9d9fedcc3.
A slice 8 build agent (CPU) started 23:00Z under slice8/PLAN-SLICE8.md. FT6 step 50 of 1,736 at 23:00:06Z.

## 2026-10-15 (UTC), entry 70

Slice 8 built (build agent, CPU, under slice8/PLAN-SLICE8.md 8004c685..., not edited); lead check and rulings (MMBU lead
session, Claude Opus 5.5). FT6 and the GPU untouched.

E:/datasets/mmbu-slice8-build/train8/run1/train_rows_s8.jsonl
f3750dc0352ed978db8db5ed0dc3d024c3688b6ccdfef2a5b1b9310465149fc2 (run2 identical, hash recomputed by the lead):
2,054 context rows, all train, on images slices 1 to 7 already trained on (R-S6A-REUSE-TRAIN-v1, reuse recorded per
row): S1 1,821, S2 104, S3 100, S4 29 (target about 3,000; the quote rule limits coverage). Lead check: 0 untrainable,
0 rows with model-written text (discern empty), specimen "Human" on all 2,054, medical domain Ophthalmology 590,
Radiology 568, Gastroenterology 447, Hematology 250, Surgery 199. Quarantine: 0 dev pairs at risk (2,411 stage-1
candidates rejected at stage 2), 9 images dropped for pairs with earlier selection or audit images; 6 dev reads
logged. Render check 0 failures. DATA-DISCLOSURE.md 82a3b183f3f2f7cd722c14a8a436971a90155a0deb956b02264f8987b3e77662
(85 sources, no new source). BUILD-SLICE8.md a53ef23d70ebbab5d20df7b86edca2fee8792be9d9cffabb01cb24f336d61609.
Lead rulings: (1) the six read-only documentation text fetches are accepted (same standing as the slice 5
abbreviations.txt fetch); (2) all rows are kept for FT7 as preregistered, including the 590 OCT and fundus rows that
keep "Optical Coherence Tomography" and "Photography" as modality, and the two weak specimen quotes (OCTDL, REAL_COLON),
each flagged to the author; (3) earlier rows stay unchanged: some images now carry two label sets (slice 7 specimen
"bone marrow" against slice 8 "Human"; "X-Ray Imaging" against "X-ray"), which FT7's per-field C will show; relabelling
is a separate proposal. Found, not caused: 3 NIH_CXR14 slice 2 train images are pixel copies of ChestX-Det images in
slice 6b's selection (2) and audit (1) splits, and one FIVES and one OCTDL slice 2 train image copy slice 2 audit or
selection images; slice 6b's audit split is therefore not independent of slice 2 training. FT7 waits for FT6's
verdict (rule P3). Not committed by the signer.

## 2026-10-16 (UTC), entry 71

FT7 amendment 1: the coordinator's four rulings on the slice 8 flags, written before any FT7 step (MMBU lead session,
Claude Opus 5.5). CPU only. FT6_4B is training (resumed by its watchdog at 23:52:27Z after the app restart, from the
step 300 checkpoint fe84b2c3...); FT6 and the GPU untouched. Data rule, author verbatim 2026-10-13: "All data sets are
acceptable as long as disclosed." No Claude-written text in any target.

1. train/ft7/PREREG-FT7-AMENDMENT-1.md e97e67225a2bcad9c2c9f9ff808ecf99e3318a570a66ff79030958dc2ca12297, amending
   PREREG-FT7.md aaf80246... (unchanged). No bar lowered or removed.
2. Rulings 1 to 3, relabel (CPU agent, resumed after the restart; lead check): make_maps.py d451b19d..., apply_maps.py
   c74839f3..., specimen_map.json 058b8d5c..., modality_map.json beb35e08... (two runs identical), docs/index.json
   31a7adcb... (fetch log lost in the restart; URL rebuilt from the file name, HTTP status unknown). Outputs
   E:/datasets/mmbu-ft7-relabel/run1 = run2: train_rows_ft6_relabel.jsonl
   864219059dae56b723b0ca8fbe2bd9913fc6bd15d738ee1d4fc405f347c787fa (27,785), train_rows_s8_relabel.jsonl
   faa9162f424cbd2153fed6f40a4cddcc6149f8e9c7c702caecad910f1d7a6515 (2,054), relabel_report.json f5251227....
   10,113 FT6 rows and 447 slice 8 rows changed, only specimen, modality and their bookkeeping keys. Images with two
   specimen labels 250 to 0; two modality labels 618 to 0; 0 context rows dropped. Specimen removed for EBHI_SEG 520,
   PCAM 545, BBBC032 24 (no organism quote); NUINSSEG Human 396 / Mouse 127 by archive folder. Ruling 2: the 590 slice
   8 OCT and fundus rows keep their names (no stored document or paper text names a paper modality for them; reasons in
   modality_map.json). Ruling 3: "Human" kept on OCTDL and REAL_COLON on stronger quotes from their own papers
   ("images of 821 patients"; participants "were patients aged 40 years or above"); flagged to the author.
3. Ruling 4 is entry 72. Its outcome: no reported number changes.
4. FT7 chain code (copies of FT6 with names changed only): ft7_chain.py f9066fc8..., ft7_run.py f1b01d25...,
   ft7_watchdog.py 7911689b..., ft7_dryrun.py a2237ff5...; byte copies train4.py 4274c0b0..., shutdown_guard.py
   2e81ceca..., locked_run.py 883f5150.... score_ft7.py 1ffc02fd... and ft7_p3.py 444e0ad1... unchanged.
5. Confound stated in the amendment: N1 to N3 (FT7_4B minus FT6_4B) measure slice 8 and the relabel together.
Not committed by the signer.

## 2026-10-16 (UTC), entry 72

Split-leak scan and corrections under coordinator ruling 4, leaky splits (MMBU lead session, Claude Opus 5.5; scan by a CPU agent started 2026-10-15 and resumed after the 23:41Z app restart; lead check and signature). CPU only, BelowNormal. FT6, the GPU and D:/gpu.lock.d were not touched. Nothing was written to D: or H:. Originals are not edited. Cleaned copies are in E:/datasets/mmbu-leakscan/clean/.

1. Scan. Every train image of the 18 training row files was compared with every selection, audit or evaluation-file image of slices 1 to 7 (slice 6 as sets a and b). 18,818 train images, 5,258 held images. Stage 1 used T1 exact pixel hash or T2 pHash at 10 bits or less, thresholds unchanged. It gave 8,816 candidates. Stage 2 used R-NEARDUP-CONFIRM-v1 and R-NEARDUP-RISK-v1. Result: 21 confirmed pairs and 9 at-risk pairs, on 28 held images and 27 train images. Train against train is not scanned (R-S6A-REUSE-TRAIN-v1).
2. Pairs by kind. All 30 pairs put a train image beside a sealed image (split selection or audit). No pair touches an evaluation file.

   | Kind | Confirmed | At risk |
   |---|---|---|
   | slice 2 MSD_HEART train to slice 2 audit | 13 | 1 |
   | slice 2 FIVES train to slice 2 audit / selection | 1 / 0 | 1 / 2 |
   | slice 2 OCTDL train to slice 2 selection | 2 | 0 |
   | slice 2 RFMID2 train to slice 2 selection | 0 | 1 |
   | slice 2 NIH_CXR14 train to slice 6b CHESTX_DET audit / selection (pixel copies) | 1 / 2 | 0 |
   | slice 4 DRAC2022_UWOCTA train to slice 6a selection (pixel copies) | 2 | 0 |
   | slice 3 CUBS_CAROTID_IMT train to slice 3 selection | 0 | 1 |
   | slice 3 ISLES2022_STROKE_MRI train to slice 3 audit | 0 | 1 |
   | slice 4 FDG_PET_CT_LESIONS_AUTOPET train to slice 4 audit | 0 | 1 |
   | slice 4 KNEE_KL_GORNALE train to slice 4 selection | 0 | 1 |

3. Cleaned copies. Each copy drops every line on a held image of a pair. All other lines are kept byte for byte. All dropped lines are split selection or audit. verify_clean.py re-checked every copy.

   | Original (SHA-256) | Cleaned copy (SHA-256) | Lines removed (audit, selection) |
   |---|---|---|
   | slice2 records.jsonl ee07ce5e... | clean/slice2/records_clean.jsonl 8dc60125ac8ded94900b6da07977d825c857807e26ced84257f1284057b439af | 19 (14, 5) |
   | slice2 rows.jsonl 29968d64... | clean/slice2/rows_clean.jsonl 6875020e7490aa267382b66f76e9e0a4419fefa3838e2a915ba6b65d82593a3e | 33 (26, 7) |
   | slice3 records.jsonl 6bbf7e46... | clean/slice3/records_clean.jsonl 2b5512e4645060a8f9403af22fe76aa2b002129b76db694afc42d479d173a5f7 | 2 (1, 1) |
   | slice3 rows.jsonl 58706b1d... | clean/slice3/rows_clean.jsonl 876c22ea1f0343014b00e21d90bb6b8f70eadc978cacca2c7e23fa7a9f2606a6 | 4 (2, 2) |
   | slice4 records.jsonl 3b2a9933... | clean/slice4/records_clean.jsonl b8d3ef2246c281666c5438afacef78ed0eb01342ddf605cf1f06110964295e4b | 2 (1, 1) |
   | slice4 rows.jsonl 6394e1b6... | clean/slice4/rows_clean.jsonl 37929e28c0140e2f7386a1b87961175cb4044a986d08fcfa85a006d57d9d1c26 | 3 (1, 2) |
   | slice6 a_run1 records.jsonl 02fa1914... | clean/slice6a/records_clean.jsonl 65857fcae72eb22d08fc733acdcfdd02e2b30a84650936123bff15a1b2a6e8cc | 2 (0, 2) |
   | slice6 a_run1 rows.jsonl d926971a... | clean/slice6a/rows_clean.jsonl a3badacfb9eff9c69cb088e01da94a1987e7dfabf5d937ab3c589d01c3ac7048 | 2 (0, 2) |
   | slice6 b_run1 records.jsonl dc581516... | clean/slice6b/records_clean.jsonl e2b49db5f65d2e6b839343a41e200e2cf3fc0669bb8291d079c5bce7ca6dd9fe | 3 (1, 2) |
   | slice6 b_run1 rows.jsonl 840ba3c2... | clean/slice6b/rows_clean.jsonl 7515ef32eaddabbbe34302f366f1d1fcd07f6fcf03aa3b49ed0d7cc7b3978c27 | 3 (1, 2) |

   All 11 evaluation files hold 0 contaminated rows. These are eval_heldout, eval_insource, eval_heldout2, eval_insource2 and the seven eval_selection files of slices 3 to 7. None of them gets a cleaned copy, because a cleaned copy would equal the original byte for byte. Each slice build had already left its quarantined images out of its own selection file.

4. Reported numbers. No reported number changes. Each number below was rescored on the cleaned file with its original scorer, its stored per-row outputs and seed 20261002. Every task, context, field and per-source key equals the stored value. The run files equal the hashes stored in the score files.

   | Number (where recorded) | Value and interval, original = clean |
   |---|---|
   | FT1 in-source answer, FT1 (entry 16, RESULTS-FT1.md) | 0.798 [0.672, 0.898]; zero-shot 0.622 [0.514, 0.711]; context 0.968 [0.935, 0.998] |
   | FT2 in-source answer, FT2 minus base (train/ft2/score_insource2.json, reported only) | +0.229 [0.175, 0.285] |
   | B4 in-source answer, FT2-4B minus Z4 (train/b4/score_eval_insource2_b4.json, reported only) | +0.268 [0.210, 0.327] |
   | FT2 B1, held-out FT2 minus base (bars_ft2.json) | +0.053 [0.033, 0.076] |
   | FT2 B2, held-out FT2 minus floor | +0.228 [0.194, 0.266] |
   | Entry 45: held-out Z4; FT2; FT2 minus Z4 | 0.181 [0.156, 0.209]; 0.230 [0.196, 0.269]; +0.050 [0.029, 0.072] |
   | Entry 47 C1, held-out FT2-4B minus Z4 | +0.048 [0.026, 0.073] |
   | Entry 47 C2, held-out FT2-4B minus floor | +0.227 [0.192, 0.266] |
   | Entry 55 G6, held-out FT3Q_4B minus Z4 | +0.082 [0.058, 0.108] |
   | Entry 62 H4, held-out FT4_4B minus Z4; reported FT4_4B minus FT3A_4B | +0.111 [0.083, 0.141]; +0.023 [0.007, 0.041] |
   | Entry 67 K2, held-out FT5_4B minus FT3A_4B | +0.0116 [-0.0016, 0.0252] |

   B3, B7, C3 and C7 are computed from the per_row block of the same score files. In all 8 rescores the per_row block equals the stored one (verify_perrow.json), so these bars stand as well. Feature validation (entry 29, features/validation.json ad8c7529...) reads held splits only for the blob checks. Their sources are BBBC039, NLM_PF and NUINSSEG. None of these is a contaminated source, and slice 1 holds no contaminated image. The validation stands. No model output and no score exists on any audit split or on any eval_selection file of slices 3 to 7.

5. Dated correction to entry 70 (2026-10-16). Entry 70 stays as written. Its paragraph "Found, not caused" counted 3 NIH_CXR14 to ChestX-Det pixel copies, one FIVES pair and one OCTDL pair. The full scan in item 2 finds more:
   - The slice 2 in-slice copies are 13 confirmed MSD_HEART audit pairs plus 1 at risk. FIVES has 1 confirmed audit pair and 3 at risk. OCTDL has 2 confirmed selection pairs. RFMID2 has 1 at-risk selection pair.
   - Slice 4 DRAC2022_UWOCTA train has 2 pixel copies in slice 6a selection.
   - Slices 3 and 4 hold 4 at-risk pairs in total.
   Slice 6b's audit split is now clean in its cleaned copy, and so are its selection split and every other sealed split above.

6. Training rows after cleaning. FT6 rows (17f2c2c6..., 27,785 rows, 14,667 images) and slice 8 rows (f3750dc0..., 2,054 rows) resolve to images on the scanned train side, with 0 rows unresolved. No row uses an image whose own record is selection, audit or evaluation. FT6 images take the train side of 26 of the 30 pairs. Slice 8 images take none. After cleaning, 0 of those held images remain in any sealed or evaluation file. The train side keeps its rows. Dev was not read in this scan. Dev overlap rests on the earlier quarantines: diag/excluded_dev_rows.json (0 FT6 rows on its drop list) and each slice build's dev check. In particular, slice 8 has 0 dev pairs at risk (entry 70).

| Record | SHA-256 |
|---|---|
| leakscan/pairs.jsonl | 5ead75082558f2c57a279c3287da49a6312291962098bb0ffc22db64db53e0a7 |
| leakscan/clean_manifest.json | a2b809621100bc1726970c4f4ea17bf8b60ef93b44be65e51985cd833009a9dc |
| leakscan/impact.json | 38c928fcfa0837230a7807c19fb09bee16d5f2473ad51731f3436f543463b293 |
| leakscan/corrections.json | 849299a14b6ddc98ed89627f95d6753ea5bb40888238bd1a81d9d3fe0930a011 |
| leakscan/verify_eval.json; verify_train.json; verify_clean.json | 83d0d973cac53223c7182333fa3e96d0e5e0f1765725f4bd7f40a3e2b8f0aa6b; 307b93da7e80d69fa19d809a70fe5029f14fe72b40b578d5e9aabde8d648c11c; f4b74e25cf8f7bfe7f3eb811f188d8f3b47099699456ae0200e36f224b49a74d |
| E:/datasets/mmbu-leakscan/stage1.jsonl; stage2.jsonl | 96de941c9bd101582ada1df6e98a4aaa63971c95726bb01bc42b63c42c35af4c; a1f829491c9a4dc0e331adb956c789ce8fe688f65162a1c389f93b119177e040 |
| Code: lscommon.py, inventory.py, scan.py, clean.py, impact.py | b28ccba8...; 61f9dd6a...; 9f4517a6...; b0fe4112...; 8d67c657... |
| leakscan/verify_perrow.json | 717f98f3db1fd02b664ff0b5bd174e69d5825edaace4d879995147d57e0b64d1 |
| Code: corrections.py, verify_eval.py, verify_train.py, verify_clean.py, verify_perrow.py | 70c9a9b9...; e5817805...; 0dbca422...; ed7f0154...; f7529f42... |

Limits. The two hashes catch copies, flips and rotations. A crop or a re-render can escape them (inferred). The at-risk pairs were not viewed one by one. They are removed by the risk rule, not by a confirmed duplicate. Not committed by the signer.
Addendum to entry 71 (00:25Z, 16 October): FT7 rows built by train/ft7/build_rows_ft7.py
c6ebb047f2c0342954f8903e464814736ffb4898c014393e1f37e4527fbba27c (inputs pinned to the entry 71 hashes; BelowNormal, rc
0): D:/datasets/discernment/ft7/train_rows_ft7.jsonl 536e06ceaaacd63568b3a71f362356f872cb5bf0cd3f0fb2c5bf1be32f2fc2f8,
29,839 rows (16,673 task, 13,166 context), 67 sources; checks passed (no repeated row_id, all trainable, all images
present, no overlap image, 0 images with two specimen or two modality values); rows_ft7_report.json. The 2 sources
beyond FT6's 65 are NEH_UT_2021_OCT and TN5000_THYROID_US (slice 8 context rows on slice 4 images; rule P1 kept slice
4's own rows out of FT6 and still does; both sources are in DATA-DISCLOSURE.md). Rule P3, the dry run and the queue
wait for "FT6 CHAIN DONE".
Correction to the entry 71 addendum (2026-10-16 00:21Z): its time "00:25Z" is wrong; it was written at about 00:18Z.
Finding, 00:20Z, not acted on (the lead's brief says FT6 is not to be touched): two FT6 trainers are alive. pid 60136
(started 22:51:47Z by driver 5056, which died in the app restart; last log line step 340 at 23:53:11Z) survived its
driver. At 23:52:27Z the watchdog judged the driver dead, released the lock as stale "(owner and step pids gone)" while
60136 was still running, and the new driver 28808 started pid 11832 from the step 300 checkpoint (resume 23:54:59Z).
Both run ft6_run.py train on the same config and out_dir; GPU memory 23,523 of 24,564 MiB; neither has logged a step
since 23:55Z (earlier steps took about 11 s, and earlier resumes logged a step within 2 to 4 min). Escalated to the
coordinator with a proposal to end the orphan 60136 and keep 11832, which the chain tracks.

## 2026-10-16 (UTC), entry 73

FT6 duplicate-trainer stall and the coordinator's kill (MMBU lead session, Claude Opus 5.5; the action was the
coordinator's). Follows the 00:20Z finding in the entry 71 addendum.

1. Stall, 23:53:11Z to 00:23:43Z. The pre-restart trainer pid 60136 (driver 5056, which died in the app restart)
   outlived its driver. The watchdog relaunched the driver at 23:52:27Z; the driver released the lock as stale
   ("owner and step pids gone") while 60136 still ran, and started pid 11832 from the step 300 checkpoint
   (fe84b2c384d9998c0949bc6f698964cc2580d29b7ddfca08d4b26fb7212ed01f, written 23:45:30Z). Two trainers on one config,
   one out_dir and one GPU (23,523 of 24,564 MiB); no step line from either after 23:53:11Z.
2. Kill. The coordinator ran taskkill /PID 60136 /T /F (child conhost 9708 ended too). The coordinator's note gives
   the time as "about 00:4xZ"; this lead measured GPU memory at 15,493 MiB at 00:21:43Z, so the kill came before
   00:21:43Z. The "do not touch FT6" brief line was superseded for this one action only. checkpoint.pt is still the
   step 300 file (60136 never wrote a later checkpoint). 11832 untouched; it logged step 310 at 00:23:43Z (loss 0.2348).
3. Cost. 40 optimizer steps (60136's steps 301 to 340) are lost and recomputed by 11832, and about 30 minutes of GPU
   time went to the stall. The training rows, order, seed and config are unchanged: 11832 resumes the same schedule
   from step 300, so the FT6 result is the preregistered run (inferred from the resume logic of train4.py, entry 66).
4. Defect. The FT5/FT6 driver and watchdog judge a step dead from recorded pids only. A trainer that survives its
   driver is invisible to them. The fix (next entry) goes into the FT7 chain copies before FT7's dry run; the live FT6
   driver and watchdog are not changed.
Not committed by the signer.

## 2026-10-16 (UTC), entry 74

FT7 liveness fix (the entry 73 defect) and the labelling decisions (MMBU lead session, Claude Opus 5.5). CPU only;
the live FT6 driver, watchdog, trainer 11832 and D:/gpu.lock.d untouched (the lock's OWNER still names FT6 driver
28808 after the test).

1. train/ft7/liveness.py fcaf62436cad0057d73499a931835a40bd6451b49ff6aa5f23f3736575d61589: same_config_pids() lists live
   processes whose command line runs ft<N>_run.py with --config equal to a given path (slashes and case normalised);
   a failed process query returns None, treated as alive (fail closed).
2. train/ft7/ft7_chain.py 8499934d6f2868ef4b5d9555068320bb20bd35b00b5bee417360f837d3f9ce34 (was f9066fc8... at entry 71):
   the stale-lock release also requires no live same-config ft*_run.py; a step does not start while a same-config
   ft*_run.py is alive (it waits, heartbeating, and honours FT7.stop); the driver heartbeats while waiting for the lock
   (before, a long lock wait left the heartbeat stale and the watchdog would kill and relaunch the driver).
   train/ft7/ft7_watchdog.py c7c4e2fe9410464d04634509f04e7bc4d0bd709a77ff2e1efbb5a2fd0baf24ee (was 7911689b...): logs
   any live same-config ft*_run.py when it relaunches; the new driver then waits for it.
3. Test on dummy processes only (train/ft7/test_liveness.py b426d8ef4a0e9e217de60c23f21594f07b362a45ab00b79d0abf02ac96590be9, dummy test_liveness_dummy_ft99_run.py,
   result test_liveness_result.json 6fc36c2956de88dac42105eea34a2b296897f0556976572532589d5aed46a3af): the chain code was executed with its directory, lock
   and heartbeat paths patched to a scratch folder. 9 of 9 checks passed: same-config found (also with backslashes and
   upper case), other config not found, lock kept while the dummy lived, released after it exited, the step waited
   for the dummy and then ran (rc 0), log lines in order. Fail-closed path (query returns None) checked separately; the
   watchdog imports cleanly. The FT6 chain files are not changed.
4. train/ft7/PREREG-FT7-AMENDMENT-1-DECISIONS.md 6780946b2a1fb23852e6ad85a3b8fe67437cbc4bf1941cd1b1e23017dc69d449: the seven labelling questions of amendment 1,
   decided where the amendment's own rules settle them (1, 2, 3a, 5, 7: keep as built), flagged otherwise (3b
   NEH_UT_2021_OCT's patient-folder quote, 4 BBBC fluorescence modality, 6 OCT submodality spelling). No row changes;
   train_rows_ft7.jsonl stays 536e06ce....
5. FT6: trainer 11832 logged step 310 at 00:23:43Z, after the coordinator's kill of 60136 (entry 73).
Not committed by the signer.

## 2026-10-16 (UTC), entry 75

Root cause corrected for entry 73, the FT6 watchdog has stopped, and a second FT7 fix (MMBU lead session, Claude Opus
5.5). Correction to entries 73 and 74, dated 2026-10-16 00:45Z.

1. Driver 5056 was alive the whole time. ft6_chain.log line 12, 00:21:36Z: "NOT released: OWNER does not carry
   mmbu-ft6-ft6_4b-5056-1792104457", after "CHAIN: ft6_4b train failed rc 1" from 5056 when the coordinator's kill
   ended its step 60136. At 23:52:27Z the watchdog logged "driver not running (last pid 5056, heartbeat 29 s old)".
   So the watchdog's tasklist check reported a live driver dead while that driver's heartbeat was fresh (inferred
   cause: a failed or empty tasklist query just after logon, which alive() read as "dead"). The new driver's
   stale-lock check used the same alive() and released 5056's lock. Entry 73's "survived its driver" is wrong; both
   drivers ran from 23:52Z to 00:21Z. 5056's token check kept it from releasing 28808's lock (good).
2. The FT6 watchdog exited at 00:22:24Z: "chain failure, not relaunching: 2026-10-16T00:21:36Z CHAIN: ft6_4b train
   failed rc 1". FT6 now runs without a watchdog: driver 28808 and trainer 11832 healthy (step 390 at 00:38Z). The
   logon task MMBU-FT6-resume is Ready, so a logon starts a fresh watchdog, which ignores failure lines older than
   its start. A driver crash before then is not relaunched. Escalated to the coordinator; nothing done to FT6.
3. FT7 second fix: ft7_chain.py 0ba2fbbc43d981a1962ac539502a6036930cdec85fabc1464392848aecea4cff and ft7_watchdog.py
   267c3b98f2e52c8e7f916b7b3464ddc6fd05e46cc0b7827af60516b88d06f2b6 (entry 74 hashes superseded). alive() fails
   closed: only tasklist's own "No tasks are running" answer counts as dead; an exception, a non-zero return or other
   output counts as alive. The watchdog counts a heartbeat younger than STALE_S (600 s) as a live driver, whatever
   tasklist says. Checks: own pid alive, pid 999999 dead, simulated query failure and error output both alive; the
   dummy-process test of entry 74 rerun, 9 of 9 (test_liveness_result.json 6fc36c29...). FT6 files unchanged.
Not committed by the signer.

## 2026-10-16 (UTC), entry 76

FT6 watchdog patched and restarted, coordinator decision (c) (MMBU lead session, Claude Opus 5.5). The coordinator
chose neither leaving FT6 unwatched nor restarting the flawed watchdog. Instead: port FT7's fixed liveness check into
the FT6 watchdog only, verify it read-only, then start it. FT6 driver 28808, trainer 11832, the lock and every
training value untouched.

1. train/ft6/ft6_watchdog.py b67381a6... (entry 66) is now 214ffc60f7b46d7d3c1b97cf5e7e5e274e0abe167130856e548973b3294b7ecc.
   The diff is limited to alive() (fail closed, as entry 75) and a driver_liveness() helper that main() now calls: a
   heartbeat younger than STALE_S (600 s) counts as a live driver. Chain-failure lines written before the watchdog's
   own start were already ignored (unchanged line: x[:20] >= t_start).
2. Read-only check, train/ft6/check_watchdog_patch.py a993f29b9c8c03da49822ea30665a1e671251a1ec68b1932a4fe260a91030c19 (imports the module without running
   main(), writes nothing under train/ft6), result check_watchdog_patch.json dca40b1e57db5b79d6a54c9eba749ae3164066304eafad810ff09e7c9a43e1f0,
   00:52:33Z: live driver 28808 alive (heartbeat 28.7 s, tasklist alive), trainer 11832 alive, 0 failure lines after
   start (1 older line ignored); a dead dummy pid (45408, exited) with a 1,000 s heartbeat reads dead; the same pid
   with a 30 s heartbeat reads alive (by design). pass true.
3. Start-ScheduledTask MMBU-FT6-resume at 00:52:44Z: watchdog pid 49208, log "check: ok; driver pid 28808 arm ft6_4b
   step ft6_4b_train heartbeat age 9 s"; no "driver launched" line; process list shows only 28808, 11832 and 49208
   for FT6. FT6 step 470 of 1,736 at 00:51Z.
Not committed by the signer.

## 2026-10-16 (UTC), entry 77

FT6 verdict by PREREG-FT6.md and amendment 1 (MMBU lead session, Claude Opus 5.5). FT6 chain: training 1,736 steps
done 04:34:53Z, lora_state.pt df63d322e4b27c2a92672eb03a6c944137c4bfc3706ba8134b7ce18b093e7dd5; dev task 04:35 to
04:50Z, dev context 04:50 to 06:16Z, held-out 06:16 to 06:59Z, all rc 0; lock released 06:59:59Z; "FT6 CHAIN DONE"
07:00:26Z. Scorer score_ft6.py 5830de49... (unchanged since entry 66). bars_ft6.json
5fc6656733567997d5f29b66be19bb26827bf7b01d563bd7bfeebea8e2d211d2, score_eval_heldout2_ft6.json 475a00a9....
Dev d09ff622 minus 12 rows (3,091), JP1, paired bootstrap, seed 20261002; C4 = FT3A_4B (rule P2).

| Bar | Result | score_v3 variant | Met |
|---|---|---|---|
| M1 dev T FT6_4B minus FT5_4B | +0.0113 [0.0032, 0.0197] | +0.0113 [0.0032, 0.0197] | yes |
| M2 dev T region rows (860) FT6_4B minus FT5_4B | +0.0256 [0.0082, 0.0439] | same | yes |
| M3 dev T FT6_4B minus FT3A_4B | +0.0123 [0.0032, 0.0217] | same | yes |
| M4 held-out answer FT6_4B minus FT3A_4B (margin 0.02) | +0.0186 [0.0031, 0.0348] | not re-read (own scorer) | yes |
| M5 dev shell FT6_4B, Pass 1 / Pass 2 | 0.9997 [0.9982, 0.9999] / 0.9984 [0.9962, 0.9993] | Pass 2 JSON found 3,091 of 3,091 | no (Pass 2 point below 0.999) |
| M6 dev Pass 1 JSON answer FT6_4B | 3,090 of 3,091 | 3,090 of 3,091 | no |

Reported: FT6_4B minus FT3A_4B adjS +0.0101 [0.0029, 0.0175], C +0.0013 [-0.0017, 0.0042], T_em +0.0107 [0.0032,
0.0181]; bone-marrow rows (42) FT6_4B minus FT5_4B T -0.0238 [-0.08, 0.0]. Arms dev T_JP1: FT3A_4B 0.2161, FT5_4B
0.2171, FT6_4B 0.2284; Pass 1 JSON found FT3A_4B 3,089, FT5_4B 3,090, FT6_4B 3,090.
Failures by id (train/ft6/format_failures_ft6.py 67d471639a6b6d0ac9cad90bda723abbeed054f0ac9f25a783962b7aa822c278, format_failures_ft6.json 0e5aaa6d94bd6cb76fa1dae108c6b661587d532593d7f74382c341d18d11cd81;
shapes only, no dev values): M6, 54d3c99568f9 (detection, a box list cut at the 768-token cap, the same row as FT5's
K4; score_v3 also finds no JSON). M5, 5 Pass 2 rows, all five-field classification sets: 40795143, 8bf44389, 048a4f9a,
505340f0, 97aee8df; score_v3 finds the predicted_metadata JSON in all 5.
Triggers: 1 is not met (M5 and M6 missed), so the submission candidate stays FT3A_4B
(E:/mmbu-submission-rehearsal/ft3a_4b_v2); nothing is packaged. 2 does not apply (M3 met). 3 does not apply. 4 does
not apply (M4 met). 5 applies: the next row set adds Pass 1 and Pass 2 format rows for these patterns (ids above); FT7's
rows are fixed by its preregistration, so this goes to the row set after FT7. Rule P3 therefore sets C5 = FT3A_4B.
Observation, no rule change: the format bars are absolute, so FT6_4B misses M6 with 3,090 rows while the standing
candidate FT3A_4B has 3,089. FT6_4B is better than the candidate on every measured dev and held-out quantity here,
format included, and the preregistered rule still keeps the candidate. Flagged to the author: a relative format bar
("no worse than the candidate") would be a bar change, which may only be preregistered for a later run.
Not committed by the signer.
Precision for entry 77 (07:06Z): "better than the candidate on every measured quantity" means point estimates. Dev
shell FT3A_4B Pass 1 0.9994, Pass 2 0.9958, Pass 1 JSON 3,089 against FT6_4B 0.9997, 0.9984, 3,090; T, adjS, T_em and
held-out answer intervals exclude 0; the C interval [-0.0017, 0.0042] includes 0, so C is not shown better.

## 2026-10-16 (UTC), entry 78

FT7 launch under PREREG-FT7.md, amendment 1 and entries 71 to 75 (MMBU lead session, Claude Opus 5.5).

1. Rule P3 (ft7_p3.py 444e0ad1..., unchanged) from bars_ft6.json 5fc66567...: ft6_4b_candidate false, so C5 = FT3A_4B;
   arms [ft7_4b]. ft7_arms.json e4f46268df4c96affbe91da301991c078b6b16cb9c523bd1806338874a8e1d12, ft7_4b_config.json
   4997a423f5f803c5a2e6d81dbe8e274b72c98548ea3188d2234311dcbcd274b9 (FT6_4B's config with train_rows, out_dir and prereg changed).
2. Dry run (ft7_dryrun.py a2237ff5680d77b994ba351e570f7289397f9be7c8aeb2623572b0e2670c3988), launched 07:02:27Z, lock taken
   07:03:57Z after the raw-native HW job (pid 4940) released it; every step rc 0: train_a 69 s (init_lora logged),
   train_b 90 s (resume logged), dev task, dev context and held-out 6 rows each; all_pass true; ft7_dryrun.json
   6e9b2b6202109f1ed8280c17ed4d4feed5126bfb45d3c3f38aff1281e0b58825. Lock released 07:08:28Z. The dry checkpoint.pt was deleted (D: space,
   11 GB free); its logs and adapter stay in D:/datasets/discernment/ft7_dry.
3. Queue: logon task MMBU-FT7-resume registered and started 07:08:57Z (pythonw ft7_watchdog.py, IgnoreNew, hidden,
   standing approval of 2026-10-13); watchdog pid 14364; driver pid 43076 took the lock 07:08:59Z; train pid 37856;
   init_lora sha 9943cdd0... (400 tensors); step 10 of 1,864 at 07:11:35Z, loss 0.218. Rows 536e06ce... (29,839).
   About 1,864 steps at about 10 s, then dev, held-out and score_ft7.py (inferred end about 15:00Z). Stop:
   train/ft7/FT7.stop. The chain carries the entry 74 and 75 liveness fixes.
Not committed by the signer.

## 2026-10-16 (UTC), entry 79

FT7 amendment 2, a candidate-replacement rule relative to the candidate (coordinator ruling; MMBU lead session,
Claude Opus 5.5). Signed 07:13:43Z, while FT7_4B trains (last train log line: step 20 2026-10-16T07:13:18 UTC); no FT7 dev, context or
held-out output exists (train/ft7/runs absent) and FT7 scoring has not started. FT6's decision stands (entry 77): FT3A_4B
stays the candidate after FT6, no post hoc swap.

1. train/ft7/PREREG-FT7-AMENDMENT-2.md a8663983c53b1c057016b266054939412a0cd79019b97db233efa45bcce37065.
   Rule R-CAND-REL-v1: a run replaces the candidate when all answer bars are met (FT7: N3, N4, N5) and it is no worse
   than the candidate by point estimate on dev shell Pass 1 strict, Pass 2 strict and the Pass 1 JSON answer count
   (intervals reported). N6 stays as a reported diagnostic. Reason: the absolute bars exclude the standing candidate
   itself (FT3A_4B Pass 2 strict 0.9958, Pass 1 JSON 3,089 of 3,091). N3 is added to candidacy (a raise).
2. train/ft7/ft7_candidate_rule.py 8257898e28367b77ef3113388b62a7c0b9d3c3f03b105b9787d04dbacada3d9f
   (reads bars_ft7.json; score_ft7.py 1ffc02fd... and the running chain unchanged; run on CPU after "FT7 CHAIN DONE").
   Stand-in smoke test (FT6 values relabelled; no decision): replaces true; with the JSON count lowered to 3,088,
   replaces false.
Not committed by the signer.
Correction to entry 79 (07:14Z): the amendment's "Written ... about 07:20Z" is wrong; it was written before 07:13:43Z,
the signing time. The file is left unchanged so its hash stands.

## 2026-10-16 (UTC), entry 80

Slice 9 plan, the FT6 trigger 5 response for the Pass 1 detection loop (MMBU lead session, Claude Opus 5.5). Written
before any slice 9 row and before any FT7 score. slice9/PLAN-SLICE9.md cb5720c2bd5c62454b361627997154ad80c9de2a766597555cc315d0a31d9c9e.
Survey (FT7 training rows, CPU): 4,456 detection task rows, at most 15 boxes, median 4, p90 4, 0 rows with 20 or more,
longest answer 312 characters; the failing dev reply (54d3c99568f9, FT5_4B, FT5_2B and FT6_4B) loops on
[34, y, 14, 14] with y step 16 until the 768-token cap (shape of our model's reply only, no dev value read). Plan: about
300 train rows with 20 to 80 boxes each, from instance masks of pooled sources (NUINSSEG, BBBC038_DSB2018), program
boxes, existing question wording, each answer under 700 tokens. The Pass 2 brace defect waits for FT7's readout (FT7
trains 1,821 S1 context rows). A CPU build agent starts now.
Not committed by the signer.

## 2026-10-16 (UTC), entry 81

Slice 9 built (CPU build agent under slice9/PLAN-SLICE9.md, entry 80, plan not edited); lead check and rulings (MMBU
lead session, Claude Opus 5.5). FT7 training and the GPU untouched.

E:/datasets/mmbu-slice9-build/train9/run1/train_rows_s9.jsonl
b86fb83c29b1e5f44b6672abf99701c8849e90e0642455d11e0d8e2a322ba470 (run2 identical; hash recomputed by the lead): 264
train detection task rows (BBBC038_DSB2018 215, NUINSSEG 49), 20 to 41 boxes per row (lead count), boxes by program from
the sources' instance masks, every answer under 700 Qwen3.5 tokens (max 699), render check 0 failures. Quarantine: 0
dev pairs at risk (26 stage-1 candidates rejected at stage 2; 4 dev reads logged); 7 BBBC038 images dropped as copies
of held-out BBBC039 images. BUILD-SLICE9.md 13ceb2d36acb5934a94ba8edd6e15c1b0a83baaa56753ffc3f7cd22f8dab3a34.
DATA-DISCLOSURE.md 53049dbf1c97d61e6eef2009e58fb6e011d73ea0e6b2655599a6c56489c3d3e7 (85 sources, unchanged count).
Lead rulings on the four deviations:
(1) Box order [x, y, w, h], not (y, x): accepted. The plan's intent was "the order the existing rows use"; its
    description was wrong. 846 of 1,334 multi-box FT7 rows, and every mask-derived source, use [x, y, w, h].
(2) Question text assembled from three verbatim fragments of existing rows, no new words: accepted (model input, not a
    target; program assembly).
(3) 264 rows, at most 41 boxes, below the plan's about 300 and 20 to 80: accepted. The 700-token limit is the
    plan's own and is kept. Known limit: the failing dev reply ran to about 50 boxes, so these rows do not reach that
    length (inferred effect: they teach closing lists of up to 41).
(4) Format A only: accepted (the 700-token check then measures exactly what the model generates).
The ten R-S9 rules in BUILD-SLICE9.md are accepted as written for this slice. Box quality notes (small NuInsSeg boxes;
20 BBBC038 rows whose box spans a multi-piece mask) are recorded, not changed. The rows wait for the preregistration of
the run after FT7.
Not committed by the signer.

## 2026-10-16 (UTC), entry 82

CORN corneal confocal dataset downloaded (MMBU lead session, Claude Opus 5.5). Author approval, verbatim 2026-10-16,
relayed by the coordinator with the question asked ("Shall it download CORN? ..."): "yes". Scope: the files of Zenodo
record 19689814 through the author's access link, nothing else.

1. Record: "CORN: corneal confocal microscope dataset", DOI 10.5281/zenodo.19689814, licence cc-by-4.0 (record
   metadata read 2026-10-16 about 07:45Z), access restricted, published 2026-04-22, no access-condition text on the
   record; access request approved 2026-10-16 06:54Z (coordinator relay). The access link is not recorded anywhere.
2. Download 08:03Z to 08:45Z, curl at BelowNormal, no GPU, into E:/datasets/corn-ccm/raw/ (new empty folder); CORN-1.zip
   resumed once after a partial transfer (curl rc 18). 705,564,554 B in 6 files, every MD5 equal to Zenodo's:
   CORN1500.zip 45a64d0a14c1fa948bc65021ce72c08088d4f25c75d754c19053ae1e2ce34daa;
   CORN-1.zip 740204a1edfea11fc835c7086840898565bac862a8a6dbe59e1319ab6f27047b;
   CORN-2.zip 5561394e0a0bc7f22106df68337f659fc0de81f23a85c08bb1fdace662b6669e;
   CORN-3.zip 6788e612970213c4343e4e4f62eb6c7b693f087c1e7746ddb4f005a95e53d72b;
   CORN-Complex.rar 4d33afed92451f6b9aabc58f4aac709bbf44289fd60406fa62eb4129dd9f16ad;
   CORN-Pro.zip 38171be5dfe4755cc0f2694df9b1efb07cd9d5ce65461a94c57f3993277f0499 (SHA-256).
   E:/datasets/corn-ccm/MANIFEST.json 0c4297302be4236b0bfb56f12eae3515572b4f0c68501b59f7c7c60c0cb800c3. A sweep of
   E:/datasets/corn-ccm, the MMBU folder and the ledger found no copy of the access token.
3. Before any training use: extraction (7-Zip, member paths checked, untrusted-data handling) and the two-stage
   near-duplicate scan against dev, every held split and the 11 evaluation files, by a CPU agent (corn/SCAN-CORN.md).
   CORN is not in FT7. Competition rule (organizer, 2026-10-09): "All datasets are acceptable as long as disclosed."
Not committed by the signer.

## 2026-10-16 (UTC), entry 83

CORN leak scan read, lead rulings and the slice 10 plan (MMBU lead session, Claude Opus 5.5). No CORN row exists;
CORN is not in FT7.

1. Scan (CPU agent; corn/SCAN-CORN.md b70f8811c898fd50cc55d2043ec3803a44751b85022ebe0dda08f71174767e00, quarantine.json
   2da58c307dda022266c62761cb0cf2afe126c220868ae228f8cbfd41852bc7a7): member listings showed 0 absolute paths, ".."
   components, links or encrypted members; archives rehashed after the scan, equal to MANIFEST.json. 6,495 images and
   7,483 label masks (384 x 384); 4,540 near-copy groups (largest 38). Matches: dev d09ff622 12 confirmed pairs, 0 at
   risk only, on 5 dev images, all CORN-2 frames (image04 with 7 augmented copies, image08, image12, image13,
   image16); held splits of slices 1 to 9, the 11 evaluation files and BBBC039: 0 (927 stage-1 candidates rejected);
   an all-pairs dev check found the same 12 and nothing else. CORN's own test images also sit outside test folders
   (195 copies, 89 in CORN-1 train). Quarantine 2,764 files (1,019 images, 1,745 labels).
2. Rules quoted: brief rule 6 forbids training on "MMBU evaluation examples, labels, annotations, or derivatives";
   author E2 (2026-10-13): source datasets allowed, "train splits only, quarantined against dev and test".
3. Lead rulings in slice10/PLAN-SLICE10.md 47a56b77eafd2a37cc9b424b9ffc75ffe14a198ccfbc4ee8dd9e6e9dfe400aa8 (written before any slice 10 row): train
   folders only (val and test out; split-less archives only through a train-only group); every near-copy group holding
   a CORN-2 member is out (5 of its frames are MMBU dev images, so others may be MMBU test images, inferred); the
   quarantine stays out; one image per group; targets only from source label files and quoted documentation; CORN val
   becomes the slice's sealed selection and audit split; disclosure as a known MMBU source. The dev-row gap (24 dev
   rows mention corneal nerves, 5 dev images match) is not explained; explaining it needs dev question text and is left
   unknown.
Not committed by the signer.

## 2026-10-16 (UTC), entry 84

FT7 shutdown and resume (MMBU lead session, Claude Opus 5.5). Checked 16:02Z; nothing changed by the lead.
The workstation went down after about 09:40Z (the trainer logged reason "wm-queryendsession" and saved a checkpoint at
step 665, k 10,640, sha 0ffa2595a98b916ae4d154fe60e9e950ecbf84b09e750923cc474778945d851d, write 0.53 s). At logon the
MMBU-FT7-resume task started watchdog 26620 (15:53:40Z); it found driver 43076 gone (heartbeat 22,372 s old) and
launched driver 41564, which released the stale lock (owner and step pids gone, no same-config process alive) and
started trainer 40216 (15:53:48Z). Resume event at step 665 with the same checkpoint sha (15:55:07Z); step 690 of 1,864
at 16:00:25Z. Process check 16:02Z: exactly one watchdog (26620), one driver (41564), one ft*_run.py trainer
(40216, config ft7_4b_config.json); the lock OWNER names driver 41564. Steps lost: 0 (shutdown save at the last step
done). Wall time lost: about 6.2 h with the machine off. Not committed by the signer.

## 2026-10-16 (UTC), entry 85

Slice 10 (CORN) built (CPU build agent under slice10/PLAN-SLICE10.md, entry 83, plan not edited); lead check and
rulings (MMBU lead session, Claude Opus 5.5). FT7 and the GPU untouched.

E:/datasets/mmbu-slice10-build/train10/run1/train_rows_s10.jsonl
a543d1ccf9b24e95faa102cfb2ba23581664b4468cf48205d6227844fe854f4c (run2 identical; hash recomputed by the lead): 600 train
rows on 600 distinct images (440 task, 160 context; lead count): region rows for corneal nerves 110, Langerhans cells
110, stromal cells 110; tortuosity classification 110 (all CORN-1 images); S1 context 160 (all CORN-Complex). Ruling
removals in order: TRAIN-ONLY 2,697 images, MMBU-FRAMES-OUT 1,192, QUARANTINE 36 more, val seal 5, ONE-PER-GROUP 634.
Quarantine rerun: 178 stage-1 pairs (75 against both dev revisions), all rejected at stage 2; 0 dev pairs at risk; 4
dev reads logged. Sealed audit file from CORN val: audit_s10.jsonl d1e4720c27ed64120a51b580b5edfaccb8969bd2fcc0d6c3ccadce0df9347a12
(237 selection, 238 audit). 21 quotes verbatim (Zenodo record page; CS2-Net, arXiv 2010.07486; MMBU paper spellings).
BUILD-SLICE10.md bb9b33f7838fde79003ed0d60d1e6b022a90d3c5b3925ccbb37145583e3be1e8. DATA-DISCLOSURE.md
d95f324b761f80e156e6f31abc3812f8d4e8b0dbc1796b8a18428ae84f3fe16d: 86 sources (CORN_CCM_IMED added as a known MMBU
source, tier Q2, 5 dev copies quarantined).
Lead rulings:
(1) The 7 new rules in BUILD-SLICE10.md are accepted as written for this slice.
(2) Modality "Confocal Microscopy" on the 160 context rows: kept, by R-FT7-MODALITY-PAPER-v1 (no paper modality name
    in the source's stored documents), the same ruling as the OCT and fundus rows (entry 71); flagged with them.
(3) Specimen "Human" on CORN-Complex from "images from 518 patients": kept; FT7 amendment 1 decision 3a (entry 74)
    already settled this evidence class (a quote that the images come from patients).
(4) Tortuosity grade k = record-page "Level k": accepted as an inference (folder order matches the page's level order;
    CORN-3 and CORN1500 agree on 106 of 144 shared groups, every disagreement one level apart; the 38 disagreeing
    groups stay dropped). Flagged: CORN-3 folder counts (31, 110, 76, 25) differ from the page's counts (54, 212,
    108, 29). The next preregistration lists the 110 tortuosity rows by id so they can be read or dropped as a unit.
(5) Format A only for task rows and the val seal: accepted.
The rows wait for the preregistration of the run after FT7, with slice 9 (entry 81).
Not committed by the signer.

## 2026-10-16 (UTC), entry 86

FT7 verdict by PREREG-FT7.md, amendment 1 and amendment 2 (MMBU lead session, Claude Opus 5.5). Chain: training 1,864
steps done 19:59:24Z (lora_state.pt 08fdddd1ce82f212eab559ddff039fbda81f959a20f0985adce31095444e0002; one shutdown
save and resume at step 665, entry 84), dev task 19:59 to 20:11Z, dev context 20:12 to 21:10Z, held-out 21:10 to
21:39Z, all rc 0; lock released 21:39:03Z; "FT7 CHAIN DONE" 21:39:23Z. score_ft7.py 1ffc02fd... unchanged; bars_ft7.json
221bd716e8c9c1410a37554cdf6fa6371473402b2f7e0a4f18e7914a9948efaa; score_eval_heldout2_ft7.json b96dad3292e2d2322255b632a7a73a5603bca1e4e7b874d9cee20fbf47cca11b. Rule P3: C5 = FT3A_4B.
Dev d09ff622 minus 12 rows (3,091), paired bootstrap, seed 20261002.

| Bar | Result | score_v3 | Met |
|---|---|---|---|
| N1 dev C FT7_4B minus FT6_4B | +0.1577 [0.1514, 0.1636] | +0.1574 [0.1511, 0.1633] | yes |
| N2 dev C on S1 rows FT7_4B minus FT6_4B | +0.1784 [0.1712, 0.1853] | +0.1780 [0.1708, 0.1849] | yes |
| N3 dev T FT7_4B minus FT6_4B (margin 0.01) | +0.0010 [-0.0061, 0.0078] | same | yes |
| N4 dev adjS FT7_4B minus FT3A_4B | +0.0425 [0.0354, 0.0498] | +0.0423 [0.0352, 0.0496] | yes |
| N5 held-out answer FT7_4B minus FT3A_4B (margin 0.02) | +0.0209 [0.0070, 0.0360] | not re-read | yes |
| N6 dev shell (absolute; diagnostic since amendment 2) | Pass 1 0.9997, Pass 2 0.9994 [0.9976, 0.9998], Pass 1 JSON 3,090 of 3,091 | n/a | no |

Amendment 2 rule (ft7_candidate_rule.py, ft7_candidate_rule.json 26a2f9e799deab20619106fe6c3ef293a8e19e020d6825e586c195b7506c5170):
answer bars N3, N4, N5 met; format against FT3A_4B no worse on all three (Pass 1 0.9997 vs 0.9994, Pass 2 0.9994 vs
0.9958, Pass 1 JSON 3,090 vs 3,089); replaces_candidate true. FT7_4B becomes the Track 3 candidate (trigger 1 as
revised); it is packaged and GPU-checked next.
Reported: dev C FT7_4B 0.4658 (FT6_4B 0.3081, FT3A_4B 0.3068); dev adjS 0.2774; dev T FT7_4B minus FT3A_4B +0.0133
[0.0045, 0.0223]. Held-out context FT7_4B minus FT6_4B -0.0895 [-0.1025, -0.0763] (by source, FT6 to FT7:
BREAST_LESIONS_USG 0.990 to 0.485, RADBOUD_EMPHYSEMA 0.893 to 0.651, KATHER2016 0.707 to 0.613, ISIC2016 0.440 to
0.650). Reading (inferred, checked on sample replies): the held-out gold keeps the sources' older words ("Ultrasound
Imaging", "X-Ray Imaging", "Tissue Section"), and FT7 now answers in the paper's vocabulary ("Ultrasound", "X-ray",
"Human") that the relabel taught; the held-out drop measures our own label vocabulary, not perception. Dev, which uses
the paper's vocabulary, rose. The one Pass 1 JSON miss is the long detection reply (slice 9 targets it).
Not committed by the signer.
Addendum to entry 86 (21:45Z): FT7_4B packaged by submission/package.py 7424fb20... (unchanged) into
E:/mmbu-submission-rehearsal/ft7_4b (200 LoRA layers merged, 4,539,265,536 parameters; ft7_4b.package.json 34817f1f106ae1b906a2dd68557223be488cfbc1308311d042335f523f89e72e);
check_package.py static pass (6,206 prompts, render_differs 0, mtp_params 0, max_new_tokens 768, the "unknown"
bad_words_ids block present). check_package.py changed 62b93132... to
ac9812119cfb6a6cff46e49ffb0fd942b222eee89bb7cb4179c99fa4305c020b for one reason: its runner-reply search covered only
train/ft3 and train/ft4, and now covers ft7, ft6, ft5, ft4, ft3; no check logic changed. The GPU check (check_package.py
gpu, FT7_4B) is queued under locked_run.py (pid 40508) behind the explainer 4K render that holds the lock since
21:39:06Z. Nothing is uploaded; uploading stays with the author.
Addendum to entry 86 (21:55Z): FT7_4B package GPU check (check_package.py gpu, plain transformers defaults, lock taken
21:44:27Z after the explainer render released it, rc 0 at 21:49:14Z; E:/mmbu-submission-rehearsal/check_gpu_FT7_4B.json
b4cda995153cd745e040469aa9d95ecdaaf472372c258b5347715632b08f8593): Pass 1, 48 rows, 48 strict, no thinking tag, 47 of
48 score the same as the runner (0 byte-identical, as at entries 62 and 68). The one difference, dev row dde0c9e36d12
(classification): package "intermediate" (em 1, jp 1), runner "coarse" (em 0, jp 0); a greedy-decoding flip between
merged bf16 weights and runtime LoRA (inferred). Pass 2: 49 rows (1 with "unknown" in the runner), 0 "unknown" after
the block, C sum 9.8 both. FT3A_4B v2 had 48 of 48 at entry 68; this check has no preregistered threshold, and the
difference is recorded, not read as a failure. Candidate: FT7_4B (E:/mmbu-submission-rehearsal/ft7_4b). Nothing uploaded.

## 2026-10-16 (UTC), entry 87

Vocabulary-harmonised held-out re-scoring, preregistered (coordinator ruling; MMBU lead session, Claude Opus 5.5).
Signed before any harmonised score is computed and before any FT8 output exists.
train/heldout_vocab/PREREG-HELDOUT-VOCAB.md 4b5401cc6a6faea2975e7b4f2974ffa815997b726609014b3669acc63b93d0c7; program
train/heldout_vocab/heldout_vocab.py 1c140725b39c09c07f4c01896618b84c6db5502922d88461a0e2174c6c30f39e (evaluate3.py
unchanged). Rules HV-MOD-v1 (modality value map from the entry 71 modality map: only-target paper names) and
HV-SPEC-v1 (preparation-type specimen becomes "Human" on the row's own "human"/"patient" quote, else the field is
not scored). Reading: the artifact reading holds if FT7_4B minus FT6_4B under harmonised gold has a lower bound above
-0.02; no bar or candidacy decision depends on it. FT6 and FT7 readings are post hoc measurements; FT8's is
preregistered.
Not committed by the signer.

## 2026-10-16 (UTC), entry 88

Held-out vocabulary re-scoring for FT3A_4B, FT6_4B, FT7_4B, by entry 87 (post hoc measurement for these arms; MMBU
lead session, Claude Opus 5.5). heldout_vocab_ft7.json 6cb68387f23bdc737e87d46f5714b77e74c236925a0a09cc4ca8c9c915dcecec; harmonised gold
E:/datasets/mmbu-heldout-vocab/harm/eval_heldout2.jsonl 217bff38942f5c214a838afa410bb87f071947d1a063f78ed916b28e892b1dfd. Changes applied: modality light
microscopy to Light Microscopy 400 rows, X-Ray Imaging to X-ray 150, Ultrasound Imaging to Ultrasound 101; specimen
"Formalin-Fixed Paraffin-Embedded Tissue Section" to "Human" on 250 rows (each row's own quote names human tissue); no
specimen field removed.

| Context, held-out (1,006 rows) | Original gold | Harmonised gold |
|---|---|---|
| FT3A_4B | 0.805 [0.783, 0.829] | 0.704 [0.690, 0.719] |
| FT6_4B | 0.806 [0.783, 0.830] | 0.698 [0.682, 0.715] |
| FT7_4B | 0.716 [0.695, 0.740] | 0.850 [0.830, 0.873] |
| FT7_4B minus FT6_4B | -0.089 [-0.103, -0.076] | +0.152 [0.135, 0.172] |
| FT7_4B minus FT3A_4B | -0.088 [-0.103, -0.074] | +0.146 [0.127, 0.168] |

Reading by entry 87: the harmonised lower bound (+0.135) is above -0.02, so the label-vocabulary reading of the
held-out drop holds; it is now measured, not inferred. Limit: neither gold is neutral; under each, the arm trained on
that vocabulary scores higher. The harmonised gold uses the MMBU paper's vocabulary, which dev and the challenge use.
No bar or candidacy decision changes.
Not committed by the signer.

## 2026-10-16 (UTC), entry 89

FT8 preregistration, slices 9 and 10 on the FT7 recipe (coordinator order; MMBU lead session, Claude Opus 5.5).
Signed before rule P4 runs, before the FT8 rows exist and before any FT8 GPU step.
train/ft8/PREREG-FT8.md e6e3d045b8e6fd6d833a2b4209b904dbf013a121498215546f0aeeab80cf1e6f.
Code: score_ft8.py df6eed7ef07cf43615cb474c2e3378645e2e5b2bcabb8b9a9516df8cc10e9e33 (copy of score_ft7.py with bars P1 to P5 and R-CAND-REL-v1
computed in place; smoke-tested on CPU with stand-ins FT7_4B as FT8_4B and FT6_4B as FT7_4B: P2, P3 and P4 equal FT7's
N3, N1 and N4; candidacy false only because the stand-in has no held-out output; 219 detection and 24 cornea dev rows),
ft8_p4.py 92f78ee7d56e51108fd7704add43e9285a7a72c94ec4aef9ae27b8fca38aa35a, build_rows_ft8.py feb36f76f0c09c2b70b9d768a029ac3e2b1560bfc8585358de162873eab610d3,
ft8_chain.py 3b193ef0429e87f21db91f19fae67a72b4e8a44f86fcdf8e5a5c60ff3a70e526, ft8_run.py 53f7a95a30c03f43ff0f8cd594acfc3a2f795b3f7ac715ad676e9199b0471520,
ft8_watchdog.py d6ae88953c8b4f9b10290e687bd100555e4f18678b1a3bc1b06c560dc482d0c2, ft8_dryrun.py 4b6d13e827e832153f473d9b8aca5ab483b28c2f2e3e422b9d441b8a730b86b7
(copies of FT7's with names changed only, diff-checked), liveness.py fcaf6243..., train4.py 4274c0b0...,
shutdown_guard.py 2e81ceca..., locked_run.py 883f5150... (byte copies).
Not committed by the signer.
Correction to entries 86 (addendum), 87 and 89 and to STATUS (2026-10-16 21:56Z, by the signer): several stated
times were estimates written ahead of the clock and are wrong. Actual UTC file write times: check_gpu_FT7_4B.json
21:49:13Z (the addendum's "21:55Z" was its writing time estimate; written about 21:50Z); PREREG-HELDOUT-VOCAB.md
21:51:28Z (text says "about 22:05Z"); heldout_vocab_ft7.json 21:51:46Z, after entry 87 was appended; score_ft8.py
21:53:10Z; PREREG-FT8.md 21:54:24Z (text says "about 22:25Z"), and entry 89 appended after it and before rule P4 and
the row build. The order of events stated in each entry is correct; only the clock times were wrong. The hashed files
keep their text so their hashes stand.
Addendum to entry 89 (21:57Z): rule P4 ran (ft8_arms.json 14a87438c2d2..., c6 FT7_4B from ft7_candidate_rule.json
26a2f9e7..., the hash recorded at entry 86; ft8_4b_config.json 96ac4be47454...). Rows: build_rows_ft8.py rc 0,
D:/datasets/discernment/ft8/train_rows_ft8.jsonl 8c99ef937a3143eeb6f50d41708ebbd80a0f5ba92d5147162b7a3f30630c0394, 30,703
rows (17,377 task, 13,326 context), 68 sources, checks passed (0 images with two specimen or modality values). Dry run
launched 21:54:54Z (pid 40980).
Addendum to entry 89 (22:03Z): dry run (ft8_dryrun.py) under the lock 21:54:54Z to 21:59:27Z, every step rc 0: train_a
67 s (init_lora logged), train_b 92 s (resume logged), dev task 35 s, dev context 41 s, held-out 37 s; 30,703 rows, 68
sources; all_pass true (ft8_dryrun.json). Dry checkpoint.pt deleted (D: space). Queue: MMBU-FT8-resume registered and
started 21:59:40Z (pythonw ft8_watchdog.py, IgnoreNew, hidden); driver 18712 took the lock 21:59:42Z; train pid 51532.
MMBU-FT7-resume removed itself at FT7 chain done. Stop: train/ft8/FT8.stop.
