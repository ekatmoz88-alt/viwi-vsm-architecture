# Architecture Overview

## Purpose

This document describes the service-mapping and code-generation architecture of the real VIWI/VSM project. The public version uses generalized terminology where required to protect proprietary implementation details.

## Documented architecture building blocks

| Building block | Generic responsibility |
|---|---|
| Mapping authoring | Captures declarative relationships between source and target interfaces |
| Input model | Represents the authored specification in a form that can be parsed |
| Validation | Checks syntax, schema constraints and selected semantic consistency rules |
| Normalized model | Provides a consistent representation for downstream processing |
| Mapping and transformation rules | Describe how input values are selected, converted and assigned |
| Template library | Defines reusable output structures |
| Generator | Applies the model and templates to produce artifacts |
| Build and integration | Checks whether generated artifacts can be incorporated into a software project |

These responsibilities summarize the project workflow at a logical level. Generalized labels are used in the public version; they do not expose restricted internal identifiers.

## Project processing sequence

1. A declarative specification is authored.
2. The specification is parsed and normalized.
3. Syntax and model constraints are validated.
4. References and dependencies are checked.
5. Mapping and transformation rules are interpreted.
6. Templates are applied to produce output artifacts.
7. Generated artifacts are reviewed and passed to build or integration checks.

The sequence reflects the documented project workflow. Installation-specific details and restricted implementation parameters are intentionally omitted.

## Mapping concept

A mapping expresses a relationship between a source value and a target value. A transformation may use the source value, constants, contextual values and validation constraints. The conceptual data path is:

`Source → Input → Mapping rule → Transformation → Output → Target`

This notation uses generalized element names in place of restricted project-specific identifiers, syntax and execution details.

## Quality considerations

A robust implementation should make the following concerns visible:

- syntax and schema validation;
- type and value compatibility;
- unresolved references and dependencies;
- deterministic generation;
- traceability from specification to generated artifact;
- diagnostics that help authors correct invalid input;
- review and build checks after generation.

These quality considerations describe the review boundaries documented for the project; exact implementation coverage depends on the corresponding project artefacts.

## Related material

- [Interactive diagrams](../index.html)
- [Evidence, scope and limitations](evidence-and-scope.md)
