# Current research architecture

WIE currently has a research/governance architecture, not an approved production service architecture. The working repository organizes a signal-universe specification, source-register contract, accepted-signal JSON Schema, research artifacts and explicit phase gates.

The current pipeline is authoritative-source discovery and traversal, candidate signal construction, semantic normalization/deduplication, cross-domain completeness passes, saturation analysis, structured quality control, independent audit and formal corpus freeze. This is the architecture shown in the public diagrams.

Future interfaces may include MCP, API and dashboard access. LPI and the remote GSC connector are potential evidence sources, not production constraints. Provider selection, production stack, tool contracts and cross-source execution semantics remain gated after research acceptance. This overview neither selects them nor presents a hypothetical implementation as existing software.

The intended long-term reasoning chain runs from observations through signals and findings to actions and verification. The Phase-1 work defines signals; it does not implement the later finding/opportunity taxonomy or action engine.

The key engineering boundary is evidentiary authority. A schema-valid record cannot become an accepted authoritative signal merely because it passes structural validation. It also needs applicable supporting sources, distinct semantics, scoped relevance, freshness assessment and research acceptance. Conflicts remain explicit until reconciled.

Current deployment is a version-controlled research workspace. No hosted WIE MCP runtime, connector orchestration, production database or SaaS tenant system was established. Container/provider choices from other projects are not imported into WIE.
