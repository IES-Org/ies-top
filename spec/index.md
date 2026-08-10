# Specification Overview

This directory contains SHACL shapes and test data for validating the IES Top Ontology.

## Table of Contents

- [Directory Structure](#directory-structure)
- [SHACL Data Validation Testing](#shacl-data-validation-testing)
  - [Prerequisites](#prerequisites)
  - [Test valid data](#test-that-valid-data-conforms-should-return-true)
  - [Test invalid data](#test-that-invalid-data-conforms-should-return-false)
  - [Notes](#notes)

## Directory Structure

- **[ies-top.ttl](./ies-top.ttl)** – This is the main RDF serialization of the IES Top Ontology, including the ontology metadata, as well as its classes and properties.
- **[validation_artefacts/](./validation_artefacts/)** – This folder contains both SHACL shapes and test data for validating ontology usage and conformance.
  - **[test_data/](./validation_artefacts/test_data/)** – Example data for SHACL validation.

Use these artefacts to validate solutions based on the IES Top Ontology.

## SHACL Data Validation Testing

This section describes how to test RDF data files against SHACL shapes using [pySHACL](https://github.com/RDFLib/pySHACL).

### Prerequisites

- Install [pySHACL](https://github.com/RDFLib/pySHACL):
  ```bash
  pip install pyshacl
  ```

### Test that valid data conforms (should return True)

Run the following command, replacing the paths as needed:

```
pyshacl -s <path to shacl file> -d <path to valid_data file>
```

Example for this repository:

```bash
pyshacl -s spec/validation_artefacts/PowerSetURIMinting.shacl.ttl -d spec/validation_artefacts/test_data/PowerSetURIMinting/PowerSet_data_pass.ttl
```

### Test that invalid data conforms (should return False)

Run the following command, replacing the paths as needed:

```
pyshacl -s <path to shacl file> -d <path to invalid_data file>
```

Example for this repository:

```bash
pyshacl -s spec/validation_artefacts/PowerSetURIMinting.shacl.ttl -d spec/validation_artefacts/test_data/PowerSetURIMinting/PowerSet_data_fail.ttl
```

### Notes

- The `-s` flag specifies the SHACL shape file.
- The `-d` flag specifies the data file to validate.

---

© Crown Copyright 2026