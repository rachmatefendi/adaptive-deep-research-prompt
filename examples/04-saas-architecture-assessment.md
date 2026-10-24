# Use case 04 — SaaS architecture and technology assessment

**Purpose:** Compare architectural alternatives and specify what must be tested before production decisions.

## Ready-to-paste research brief

Use with [`PROMPT.md`](../PROMPT.md).

```text
RESEARCH TOPIC:
Architecture alternatives for a multi-tenant SaaS platform
that combines messaging workflows, AI analysis, billing,
and external payment integrations.

Research Objective:
Compare viable architecture patterns by tenant isolation,
security, observability, operational complexity, maintainability,
cost drivers, and migration reversibility.

Research Context:
Early-stage product serving Indonesian customers; do not assume
production traffic, SLOs, or provider pricing without evidence.

Expected Outcome: TECHNICAL
Target Audience: ENGINEERS
Research Depth: COMPREHENSIVE
Geographic Scope / Jurisdiction: INDONESIA with global technical references
Research Time Horizon: CURRENT
Output Language: ENGLISH
Writing Style: TECHNICAL
Evidence Standard: STANDARD
Governance Profile: MATERIAL_DECISION_RESEARCH
Deliverable Format: TECHNICAL REPORT

Additional Requirements:
Evaluate modular monolith versus service decomposition where
material. Use current official documentation for provider-specific
limits/pricing/security claims. Identify tenancy boundaries,
auditability, authorization, data retention, resilience, and
integration failure modes. Separate design proposals, implemented
controls, tested capabilities, and production-readiness criteria.
Do not implement, deploy, or modify a system.
```

## Expected output characteristics

Context-specific trade-off matrix, data/tenant boundary considerations, integration dependencies, staged architecture recommendation, and testable acceptance criteria.

**Critical watch-out:** A conceptual security model or a vendor feature page does not prove a deployed system is secure or production ready.
