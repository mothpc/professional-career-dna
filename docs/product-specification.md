# Product specification

Status: discovery decisions accepted; documentation baseline under review. Target: v0.1.0.

## Vision and audience

Help professionals across industries understand the work they actually do, reflect on their strengths and preferences, explore realistic career alternatives and plan their next milestone. Technology is an initial reference domain, not a universal taxonomy. Users choose their own model and compatible agent environment; support must be tested rather than assumed.

## Experience

Start from an existing conversation, CV, workspace or a question about career direction. Reuse relevant evidence. Ask one meaningful personal question at a time; research public information independently and verify it before claiming it. Reflect, challenge assumptions and allow tangents and early exit. Present provisional conclusions with gaps; seek user confirmation before persisting a baseline. Do not force a sequential pipeline.

## Functional requirements

| ID | Requirement |
|---|---|
| FR-01 | Adaptive discovery with coverage tracking |
| FR-02 | Responsibility-to-role mapping, professional identity and adaptive DNA |
| FR-03 | Evidence-backed role similarity, separate from readiness and preferences |
| FR-04 | Career positioning, alternatives and conceptual trajectory |
| FR-05 | Target readiness, skill gaps, learning roadmap and verified learning resources |
| FR-06 | User-owned Markdown living documents and confirmed milestone snapshots |
| FR-07 | Adaptive visual reports, offline HTML5 and A4 PDF when capabilities permit |
| FR-08 | Private default report and user-approved shareable variant |
| FR-09 | Independent skill invocation and capability-aware fallback |
| FR-10 | Preserve fact/inference/unknown distinction and citations throughout |

## Non-goals

No SaaS, backend, database, authentication, custom agent orchestration, training/fine-tuning, proprietary job database, psychometric assessment, automated recruitment scoring or provider lock-in. No guarantees of promotion, compensation or professional certification.

## Releases

v0.1.0: discovery, DNA, positioning, growth, report; workspace and snapshots. v0.2.0: reflection and historical comparison. Later candidates: job-description matching and opportunity analysis; not committed scope. See [acceptance criteria](mvp-acceptance-criteria.md).
