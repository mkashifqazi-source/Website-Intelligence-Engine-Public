# Signal and provenance models

## Observation, signal, finding and outcome

An observation is a directly seen fact. A signal is a normalized meaningful property derived from observations. A finding interprets signals into a problem/opportunity/state. An outcome is a downstream result such as indexing, citation, clicking or conversion. These types carry different authority.

The accepted-signal JSON Schema requires semantic identity, domain/subdomain, definition, observed property, value/unit, entity scope, applicability, platform relationships, temporal/history significance, provenance references, evidence class, confidence, observability, availability constraints and limitations. It rejects unknown properties and excludes the unsupported-claim class from accepted signals.

A signal's evidence class, confidence, availability and ranking-factor status are separate fields. A deterministic diagnostic can be high-confidence without being a ranking factor. A platform outcome is not proof of causation by a particular signal.

## Source-register contract

Sources have stable semantic identities plus publisher, resource identity, source type/tier, retrieval and status dates, version, access/freshness assessment and supersession links. A record represents a particular citable resource state rather than an entire publisher.

Signals reference source IDs. Resolution and primary-source support are cross-artifact checks; a JSON Schema alone cannot prove that a cited resource exists or supports a particular conclusion. The inspected source-register document is a contract, not an implemented source schema or populated authoritative register.

## Exclusions and uncertainty

Unsupported/obsolete/disputed claims belong in an anti-signal register. Unresolved or unobservable concepts belong in a frontier register. These do not silently enter the accepted dictionary. Source supersession retains history rather than overwriting prior evidence.
