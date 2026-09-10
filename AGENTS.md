# Development entry point

Apply LYNCA Development Standard v1.0:
https://linear.app/lynca/document/00-lynca-development-standard-ce99ee6fb72d

Repository: LYNCA-OS/lynca-image-pipeline
Purpose and ownership: Early LYNCA image standard and prompt
(`lynca/standards/image2_v1.5.md`, `lynca/prompts/run.txt`). Document-only; no code,
tests, deployment, or CI. The 2026-09-09 portfolio audit records OCS describing this
repository as retiring; the active image workflow lives in `lynca-webtool-imageproc`
(Image2 v1.6) and `lynca-runtime-cardimg`.
Development guide: `README.md`. Changes are Routine class: content, diff, and reference
checks.
Relevant contracts: none beyond the two files above; treat them as historical reference,
not the active standard.

Before editing, verify workspace identity and preserve unrelated changes.
Follow scoped instructions. Use the smallest reliable change and verification
appropriate to its risks. Continue within established authorization.
Protect originals, human edits, access boundaries, and external side effects.
Report observed results; distinguish implementation, merge, deployment, and
acceptance. Keep skipped and unknown checks explicit.

Repository-specific constraints: do not evolve the standard or prompt here. Make
image-standard changes in the active repository and update this one only to point to it.
