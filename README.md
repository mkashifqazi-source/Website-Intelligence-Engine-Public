# Website Intelligence Engine

A research-first foundation for provenance-aware website signals spanning search, AI discovery and website outcomes.

Public Technical Overview · Private Development Repository

## Overview

WIE aims to turn scoped observations into defensible website intelligence. Its current engineering work defines the evidence and signal contracts before selecting production architecture or building an MCP service.

## Problem

Website analysis often mixes crawlability, indexability, indexing, citation and conversion, or treats diagnostics as ranking factors. Combining more providers cannot fix those semantic errors unless evidence authority, freshness, scope and uncertainty are explicit.

## System Architecture

The current architecture is a research pipeline, not a production MCP topology.

~~~mermaid
flowchart TD
  E[Primary sources and standards] --> R[Provenance / source register contract]
  R --> C[Candidate signal corpus]
  C --> N[Normalization and completeness]
  N --> Q[QC / saturation / independent audit]
  Q --> F[Formal freeze gate]
  F -. later authorization .-> P[Future product and MCP design]
~~~

## Core Components

Signal-universe specification, evidence classifications, source-register contract, accepted-signal JSON Schema and programme acceptance gates. Observation, signal, finding and outcome remain distinct models.

## Key Technical Workflows

Traverse evidence → construct semantic candidates → normalize/deduplicate → assess cross-domain completeness and saturation → QC → independent audit → freeze. Unsupported claims and unresolved concepts are retained separately.

## Engineering Decisions

Research precedes product architecture. Existing LPI/GSC assets remain integration candidates rather than architecture constraints. Confidence, evidence class, availability and causal/ranking status stay separate.

## Reliability / Safety / Validation

Schema validity is only structural. It cannot prove evidence alignment, source freshness or corpus completeness. Generated research without actual evidence is rejected. Later sources supersede earlier evidence explicitly.

## Technology Stack

Current artifacts use Markdown, Mermaid in this showcase, and JSON Schema for accepted research records. The production stack, provider set, MCP transport implementation and hosting are not selected.

## Testing

Specified validation includes structural checks, reference integrity, semantic QC, completeness/saturation and independent audit. Executable validator/corpus acceptance results were not established; none were run here.

## Current Status

Research foundation, Phase 1 in progress. No production WIE MCP is claimed. This showcase documents the present research contracts and engineering boundaries.

## Technical Documentation

- [architecture](docs/architecture.md)
- [data model](docs/data-model.md)
- [workflows](docs/workflows.md)
- [testing and validation](docs/testing-and-validation.md)
- [reliability and failure model](docs/reliability-and-failure-model.md)
- [security and authority](docs/security-and-authority.md)
- [technical decisions](docs/technical-decisions.md)
- [project status](docs/project-status.md)
- [research gates](diagrams/research-gates.md)

## Repository Notice

This repository contains the public technical documentation for the project. The production source code and internal development materials are maintained separately and are not published here.
