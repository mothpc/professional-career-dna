# Skill contracts

Six outcome-oriented skills are planned; first five ship in v0.1.0. All accept relevant existing conversation or workspace evidence. No mandatory prior invocation; if information is missing, verify public facts or ask one personal question at a time. Return provisional findings when requested and disclose gaps. Persist confirmed outputs only.

| Skill | Responsibility | Inputs | Outputs |
|---|---|---|---|
| career-discovery | Understand the person and collect evidence | Conversation, CV, existing profile | profile.md, evidence.md |
| professional-dna | Analyze identity, competency and role alignment | Responsibilities, outcomes, role research | professional-dna.md |
| career-positioning | Explore career landscape and alternatives | Relevant profile, verified role definitions, DNA when available | career-positioning.md |
| career-growth | Assess readiness and plan development | Target, evidence, preferences, constraints, verified resources | career-growth.md |
| career-report | Present validated findings without changing them | Confirmed documents, disclosure choice, render capabilities | HTML5, PDF or Markdown fallback |
| career-reflection | Review changes and coordinate updates (v0.2.0) | Current workspace and comparable historical snapshot | Reflection and confirmed baseline updates |

## Shared behavior

Use concise SKILL.md instructions with name/description and progressive references. Domain guidance is optional and extensible. Verify external information, distinguish fact/inference/unknown, record sources and confidence. Do not assume a host has browsing, files or native skill installation. Preserve user control and minimize disclosure.

## Report contract

Agent chooses relevant sections and visualizations. Renderer consumes validated derived JSON; exact schema remains open. Standard chart types: radar, horizontal bars, direct-labeled scatter, career trajectory, roadmap and competency matrix. Unknowns must remain unknown. Self-contained HTML uses embedded SVG or HTML/CSS without required JavaScript; mobile-first and print A4 portrait. Include evidence limitations, readable typography and verified book covers only when available and permitted. Missing cover assets use clearly labeled text, not fabricated covers. Private default; explicit review before shareable output. Validate content integrity, layout and privacy.
