# Workspace contract

Markdown is the authoritative, human-editable source. This is a proposed initial file layout consistent with accepted persistence decisions; exact schema and migrations remain technical design work.

```text
career-workspace/
  profile.md
  evidence.md
  professional-dna.md
  career-positioning.md
  career-growth.md
  snapshots/
  reflections/
  reports/
```

Keep the workspace outside the public source repository. Do not commit real personal records. A host without file access can provide Markdown for the user to save.

| Document | Owner | Contents |
|---|---|---|
| profile.md | career-discovery | Background, official title, responsibilities, preferences, goals, constraints |
| evidence.md | career-discovery | Stable evidence identifiers, source, date, claims and verification status |
| professional-dna.md | professional-dna | Mapping, competencies, similarity, rationale and confidence |
| career-positioning.md | career-positioning | Role research, axes, alternatives, trajectory and uncertainty |
| career-growth.md | career-growth | Target readiness, gaps, learning and measures |
| reports/ | career-report | Derived HTML/PDF and optional derived render input |
| snapshots/, reflections/ | lifecycle/reflection | Confirmed historical baselines and change history |

Other skills read relevant content but must not silently overwrite conclusions outside their boundary. If contradictions appear, flag them and obtain confirmation before updating affected documents. Provisional analyses must not be represented as confirmed.

Living documents represent current confirmed state. Create an immutable milestone snapshot only when the user confirms a baseline or significant change; retain date, rubric/version and evidence links. Avoid overwriting same-day history; exact naming/versioning is open. MVP supports snapshot creation as a workspace operation without requiring the deferred reflection skill. Historical comparison and reflection are v0.2.0.

Derived JSON is generated for rendering and validated against the agreed report contract. Never treat it as canonical. Shareable artifacts must not retain excluded content in metadata, hidden markup, assets or attachments.
