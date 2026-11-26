# ADR 0004 — Privacy and disclosure boundary

Status: Accepted direction (decision 011).

Context: Career evidence can include sensitive personal and employer information. Provider-managed privacy alone cannot govern project behavior; strict local-only would prevent some hosts.

Decision: Private user-owned workspace outside public repository; minimize external disclosure, no built-in telemetry, private reports by default, explicit user review for shareable outputs. Use fictional examples.

Consequences: Logical boundary enforced through instructions and artifact checks, not a guarantee of local processing. Provider policies remain outside project control; test against hidden-data leakage.
