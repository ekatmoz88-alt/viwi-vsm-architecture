# VIWI / VSM — Architecture Documentation

> **Real project documentation.** This repository contains a sanitized architecture description of the VIWI/VSM project, based on project materials. It documents the service-mapping and code-generation workflow while replacing restricted identifiers and omitting confidential source code, manuals and configuration details.

## Scope

The material describes the documented VIWI/VSM workflow in which declarative mapping models are checked, normalized, transformed and used to produce software artefacts. Public labels are generalized where required to protect proprietary project details.

- [Architecture overview](docs/architecture.md)
- [Evidence, scope and limitations](docs/evidence-and-scope.md)
- [Interactive diagrams](index.html)
- [Diagram source files](diagrams/)

## Architecture diagrams

1. Project architecture — authoring, validation, model processing and output.
2. Generation pipeline — the documented sequence from input to generated artefacts.
3. Mapping data flow — source, transformation and target responsibilities.
4. Quality gates — validation and review boundaries.

## Publication boundaries

- The diagrams describe the real VIWI/VSM project at a sanitized logical-architecture level; they are not a reconstruction of every physical server or installation-specific setting.
- Proprietary source files, manuals, schemas, configuration data, identifiers and error catalogues are not published.
- Generalized labels protect restricted implementation details while preserving the documented project workflow.

## Viewing locally

Open `index.html` in a browser. Mermaid is loaded from a public CDN, so an internet connection is required to render the diagrams.

## Status

**Sanitized documentation of a real VIWI/VSM project.**
