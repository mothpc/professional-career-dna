# ADR 0001 — Skills-first and progressive disclosure

Status: Accepted direction (decisions 001, 002, 004, 010, 013).

Context: Users select their own agent/model and may enter at any stage. A monolith or mandatory pipeline adds coupling and context overhead.

Decision: Six independent outcome-oriented skills, five in MVP; use concise instructions and load relevant references on demand. Domain-agnostic core, extensible guidance, host-driven research and reasoning. No dedicated orchestration runtime.

Consequences: Host capabilities vary; portability needs testing. Shared behavior must remain consistent across skills. Packaging and discovery conventions remain open.
