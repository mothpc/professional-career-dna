# ADR 0003 — Separate reasoning and rendering

Status: Accepted direction (decision 009).

Context: Agent-generated charts and PDF may vary in appearance or fail when scripts are blocked; fixed content limits adaptability.

Decision: Agent selects validated content and chart types; deterministic utilities render validated derived input into offline mobile-first HTML and A4 PDF. No required JavaScript. Render must not alter assessment.

Consequences: Reproducible presentation and independent tests; renderer dependencies and schema need design. Hosts lacking tools return honest lower-capability outputs.
