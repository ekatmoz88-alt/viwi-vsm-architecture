# VIWI / VSM — Sanitized Architecture Study

> **Portfolio demonstration only.** This repository contains an independently authored, technology-neutral reference model for explaining service-mapping and code-generation concepts. It is not an implementation description, a reverse-engineered product specification, or a reproduction of any confidential manual or source code.

## Scope

The material illustrates a generic workflow in which a declarative mapping model is checked, normalized, transformed and used to produce software artifacts. All component names, interfaces and flows are intentionally generic.

- [Architecture overview](docs/architecture.md)
- [Evidence, scope and limitations](docs/evidence-and-scope.md)
- [Interactive diagrams](index.html)
- [Diagram source files](diagrams/)

## Diagrams

1. Reference architecture — authoring, validation, model processing and output.
2. Generic generation pipeline — the conceptual sequence from input to artifacts.
3. Mapping data flow — source, transformation and target responsibilities.
4. Quality gates — validation and review boundaries.

## Important limitations

- The diagrams are conceptual teaching aids, not verified product topology.
- They do not assert the internal design, runtime behavior, deployment, technology adapters, algorithms or exact component boundaries of VIWI/VSM.
- No confidential source files, manuals, schemas, configuration data, identifiers or proprietary error catalogs are included.
- Any resemblance to a particular implementation is incidental to the use of common software-architecture patterns.

## Viewing locally

Open `index.html` in a browser. Mermaid is loaded from a public CDN, so an internet connection is required to render the diagrams.

## Status

**Demonstration model — not an as-built architecture and not a product specification.**
