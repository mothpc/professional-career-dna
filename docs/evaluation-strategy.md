# Evaluation strategy

Use scenario-based outcome evaluation for agent behavior and deterministic software tests for artifacts. Do not require identical prose across models. No cross-model results exist yet.

## Scenarios

Use fictional profiles only: junior engineer, senior architect, marketing professional, finance professional, career switcher, experienced manager, incomplete profile, contradictory evidence, inflated self-assessment, returning user, host without web access, sensitive career information. Include technology and non-technology domains. Returning-user historical comparison belongs to v0.2.0; snapshot integrity is MVP.

## Outcome rubric

Review context reuse, meaningful one-question interviewing, evidence grounding, verified research, assumption control, critical reflection, role/title separation, similarity/readiness separation, uncertainty, privacy and actionable recommendations. Record concrete observed evidence and failures for each dimension. Proposed rating categories: pass, partial, fail, not applicable. Calibration, thresholds, repeat counts and evaluator agreement remain open. Privacy leaks and fabricated sources are release blockers regardless of aggregate quality.

Record host/model version, skill revision, tool availability, scenario revision, date, transcript or redacted evidence, rubric results and limitations. At least two agent environments must be tested for MVP; model-agnostic intent is not a compatibility guarantee. Start with manual evaluation and regression fixtures; automate when justified.

## Artifact checks

Validate schema and data fidelity, chart values and direct labels, readable mobile layout at 390px, no required JS/CDN, offline rendering, A4 portrait dimensions and pagination, font/language support, exclusion of sensitive content from visible and hidden fields, and reproducible semantic content. Inspect rendered pages; do not infer visual quality from successful export. Document environment and actual results.
