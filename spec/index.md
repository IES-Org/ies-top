# Specification Overview

This directory contains SHACL shapes and test data for validating the IES Top Ontology.

- **[ies-top.ttl](./ies-top.ttl)** – This is the main RDF serialization of the IES Top Ontology, including the ontology metadata, as well as its classes and properties.
- **[validation_artefacts/](./validation_artefacts/)** – This folder contains both SHACL shapes and test data for validating ontology usage and conformance:
  - **[IntermittentTimespan.shacl.ttl](./validation_artefacts/IntermittentTimespan.shacl.ttl)** – SHACL shape ensuring that any state which is part of an `IntermittentTimespan` is also a `TemporallyIntermittentState`.
  - **[PowerSetURIMinting.shacl.ttl](./validation_artefacts/PowerSetURIMinting.shacl.ttl)** – SHACL SPARQL constraint to check that PowerSet URIs follow the required naming pattern (e.g., `SetOf...`).
  - **[test_data/](./validation_artefacts/test_data/)** – Example data for SHACL validation:
    - **[PowerSetURIMinting/](./validation_artefacts/test_data/PowerSetURIMinting/)** – Test cases for PowerSet URI minting:
      - **[PowerSet_data_fail.ttl](./validation_artefacts/test_data/PowerSetURIMinting/PowerSet_data_fail.ttl)** – Failing test case: demonstrates an incorrect PowerSet URI.
      - **[PowerSet_data_pass.ttl](./validation_artefacts/test_data/PowerSetURIMinting/PowerSet_data_pass.ttl)** – Passing test case: demonstrates a correct PowerSet URI.

Use these artefacts to implement, extend, or validate solutions based on the IES Top Ontology.
