# Governance profiles and authority boundaries

The master prompt can support consequential research without pretending to be a regulator, board committee, professional adviser, or technical control plane.

## Profile selection

| Profile | Use when | Does not imply |
|---|---|---|
| `STANDARD_RESEARCH` | Exploratory, descriptive, educational, or ordinary scholarly research | A corporate decision process |
| `MATERIAL_DECISION_RESEARCH` | Findings affect capital, compliance, major architecture, security, or irreversible commitments | Investment approval or legal authorization |
| `AFGS_MDGR_REFERENCE` | AFGS/MDGR explicitly appears in the task or is itself the research subject | A live AFGS/MDGR runtime, formal MDGR verdict, or GEG enforcement |

### AFGS/MDGR reference-only overlay

AFGS and MDGR are **not** generic labels to apply to unrelated governance topics. For a specific AFGS/MDGR question, the prompt may reference the user's own normative materials if provided or accessible and may distinguish AI Founder OS, EASGF, MDGR, IAR, EPS, PCR, and GEG according to that source. Never invent missing version specifications, official decisions, component responsibilities, or policy authority.

A research prompt cannot modify or certify a frozen normative baseline. Its output does not establish runtime enforcement, external verification, production readiness, or compliance with SC2/SC3 assertions.

**Research ≠ Recommendation ≠ Decision ≠ Approval ≠ Execution Authorization.**

The analytical Research Contract is a working scope record and not an institutional approval. A governance verdict must come from an authorized mechanism. Any consequential action requires independent permission and actual enforcement in the deployment environment.

## Suggested architecture if implemented as an agent later

This repository ships *no software agent*. If adapted into one:

- Start with a single research agent, real retrieval tools, and an inspectable structured Research Contract.
- Keep tools for reading separate from tools that create, update, publish, or execute.
- Constrain tool permissions and require human approvals for consequential side effects.
- Maintain source and tool logs with provenance and timestamps where permitted.
- Run behavioral tests for denied access, conflicts, injected instructions, and scope drift.
- Never treat a prompt-only denial as a substitute for runtime authorization.

Those are implementation recommendations, not claims that such controls exist here.
