# Limitations, status, and responsible use

**Document status:** Released template documentation at `v1.0`; not empirically benchmarked or externally validated.

## What this is

A reusable set of instructions encouraging better research behavior: explicit scope, evidence labels, source provenance, counter-evidence, access-status reporting, adaptive domain methods, and bounded conclusions.

## What this is not

- A guarantee of source correctness or a hallucination-proof system.
- A scholarly systematic review without an actually executed and documented review methodology.
- A browsing, document-parsing, statistical, or verification tool.
- A cryptographic provenance system, an auditable chain-of-custody implementation, or a research database.
- An investment committee, professional license, judicial/regulatory interpretation, or organizational approval process.
- A deployed AFGS, MDGR, policy enforcement, or GEG gateway.
- A protection mechanism that can guarantee immunity to prompt injection.

## Principal residual risks

1. **Model instruction noncompliance:** long prompts can be compressed or ignored, particularly under context pressure.
2. **Partial access:** abstracts or press summaries may not contain controlling details.
3. **Reference fabrication:** prompts reduce but cannot eliminate invented links, section numbers, quotations, or DOI identifiers.
4. **Research selection bias:** search engines and retrieval tools may omit relevant primary sources or overemphasize accessible sources.
5. **Circular source dependency:** independence is difficult to prove without tracing citation chains.
6. **Rapidly changing facts:** law, market data, scientific findings, and technology documentation may be superseded.
7. **Inference limitations:** causal conclusions, risk scores, or forecasts require methods and valid data beyond fluent text.
8. **Untrusted retrieved content:** external instructions can be malicious; behavioral isolation needs testing and potentially runtime enforcement.
9. **Authority confusion:** the model can write a recommendation, but cannot authorize a corporate or legal action.

## Practical safeguards

- Read cited originals and relevant sections, especially for consequential claims.
- Record a clear as-of date for dynamic topics.
- Check effective dates and amendments for legal content.
- Independently validate material numerical models.
- Do not upload confidential documents without appropriate handling and permission.
- Subject consequential output to appropriate qualified human review.
- Run controlled evals before using this prompt in an automated production workflow.

Use the results as research input, not as final institutional authorization.
