# SHACL Data Validation Testing

This README describes how to test RDF data files against SHACL shapes using [pySHACL](https://github.com/RDFLib/pySHACL).

## Prerequisites

- Install [pySHACL](https://github.com/RDFLib/pySHACL):
  ```bash
  pip install pyshacl
  ```

## Test that valid data conforms (should return True)

Run the following command, replacing the paths as needed:

```
pyshacl -s <path to shacl file> -d <path to valid_data file>
```

Example for this repository:

```bash
pyshacl -s spec/validation_artefacts/PowerSetURIMinting.shacl.ttl -d spec/validation_artefacts/test_data/PowerSetURIMinting/PowerSet_data_pass.ttl
```

## Test that invalid data conforms (should return False)

Run the following command, replacing the paths as needed:

```
pyshacl -s <path to shacl file> -d <path to invalid_data file>
```

Example for this repository:

```bash
pyshacl -s spec/validation_artefacts/PowerSetURIMinting.shacl.ttl -d spec/validation_artefacts/test_data/PowerSetURIMinting/PowerSet_data_fail.ttl
```

## Notes

- The `-s` flag specifies the SHACL shape file.
- The `-d` flag specifies the data file to validate.
