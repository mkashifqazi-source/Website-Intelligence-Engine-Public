# Technical decisions and gates

## Freeze the signal universe before production architecture

**Context:** The mission spans search, AI discovery, content, performance, accessibility, users, competitors and business outcomes.

**Decision:** Research, normalize, independently audit and freeze the signal corpus before Phase 2 or production architecture selection.

**Why:** Existing connectors and familiar SEO tools must not prematurely constrain discovery.

**Alternatives considered:** The governing instructions explicitly reject starting implementation/provider selection before the research gate.

**Consequences:** Product implementation waits; research requires its own reproducibility and acceptance discipline.

**Current status:** Active gate; Phase 1 in progress.

## Separate evidence classifications from confidence and causal status

**Context:** A meaningful signal can be observed without being a proven ranking mechanism.

**Decision:** Track evidence class, confidence, observability, availability and ranking-factor status separately.

**Why:** Avoid upgrading a diagnostic or correlation into a universal mechanism.

**Alternatives considered:** Unsupported universal scores and ranking-factor assertions are explicitly excluded by the specification.

**Consequences:** Richer records and stronger interpretation constraints.

**Current status:** Supported by specification and accepted-signal schema.

## Preserve supersession and rejected evidence history

**Context:** Platform documentation and research conclusions change.

**Decision:** Retain historical provenance and explicit replacement links; rejected research cannot become input by convenience.

**Why:** A current conclusion needs an auditable relationship to earlier evidence.

**Alternatives considered:** Silent overwriting/deleting historical research is explicitly disallowed.

**Consequences:** More lineage management; readers can distinguish correction from original observation.

**Current status:** Governance/source-register contract; complete corpus machinery remains unverified.
