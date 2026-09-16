# Changelog

**Repository:** `IES Top Ontology (ies-top)`<br>
**Description:** `Tracks all notable changes, and version history following Semantic Versioning.`

All notable changes to this project will be documented in this file.

This project follows **Semantic Versioning (SemVer)** ([semver.org](https://semver.org/)), using the format:

`[MAJOR].[MINOR].[PATCH]`

For ontology development, Semantic Versioning is interpreted as follows:

- **MAJOR** (`X.0.0`) - Changes that are not backward-compatible and may require users to update data, queries, mappings, integrations or implementations.
- **MINOR** (`0.X.0`) - Backward-compatible additions or enhancements to the ontology.
- **PATCH** (`0.0.X`) - Backward-compatible corrections that do not materially change the intended ontology model.

---

## [0.2.0] - 2026-08-23
### Added
- `Extent` class as the root of the individuals hierarchy, allowing for individuals that are not necessarily spatiotemporal. This makes explicit IES-Top's commitment to Extensionalism, upon which Four-Dimensionalism is subsequently built, and moves IES-Top closer to David Lewis' principle of plenitude, under which "the worlds are many and varied" and may differ fundamentally from our own — including worlds in which "totally different laws govern the doings of alien particles with alien properties". `SpacetimeExtent` is now a subclass of `Extent`
- `WorldboundExtent` and `TransworldExtent` classes. In RC1 these distinctions were represented through class definitions; they are now explicit classes in their own right
- `RegularSpacetimeExtent` class as a subclass of `SpacetimeExtent`, providing the foundation for updates to IES-Core in relation to spatial objects, relative spaces and coordinate systems. Note: in practice, virtually all usage of IES relate to regular spacetime extents
- `World` class as the superclass of the existing `Universe` class, allowing for worlds irrespective of whether they are spacetime worlds or not
- `connected` and `disconnected` relations
- SHACL validation file for for all classes and properties

### Changed
- Renamed `SpatiotemporalExtent` to `SpacetimeExtent`. This makes clearer that, at this level, we are talking about "chunks" of spacetime (in a spacetime world), aligns the terminology with the foundational spacetime literature originating with Minkowski and Einstein, and provides a shorter and cleaner term in the RDF implementation
- Refined the pattern for continuous and intermittent states, giving it a standard mereotopological foundation based on self-connection and self-disconnection, itself built on the newly introduced `connected` and `disconnected` relations
- `couple` and `groundingRelation` made instances of `owl:ObjectProperty` rather than the more general `rdf:Property`;

## [0.1.0] - 2025-10-10

### Added
- Initial ontology structure in RDF
- ODM-UML Diagrams and descriptions

[keep-change-log]: https://keepachangelog.com/en/1.0.0/
[semver]: https://semver.org/spec/v2.0.0.html
[0.2.0]: https://github.com/IES-Org/ies-top/releases/tag/v0.2.0
[0.1.0]: https://github.com/IES-Org/ies-top/releases/tag/v0.1.0

---

## How to Update This Changelog

1. When making changes, update this file under the **Unreleased** section.
2. Before a new release, move changes from **Unreleased** to a new dated section with a version number.
3. Follow **Semantic Versioning** rules to categorise changes correctly.

---

**Maintained as part of the Information Exchange Standard initiative.**

© Crown Copyright. This work forms part of the Information Exchange Standard initiative and is currently under the custodianship of the UK's Department for Business, Innovation, Science and Trade (BIST), acting on behalf of a cross-government group of stakeholders.
  
Licensed under the Open Government Licence v3.0.

For full licensing terms, see [OGL_LICENSE.md](OGL_LICENSE.md).