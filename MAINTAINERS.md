# Maintainers

**Repository:** `IES Top Ontology (ies-top)`  
**Description:** `Lists maintainers responsible for reviewing issues, approving changes, and overseeing development.`

<!-- SPDX-License-Identifier: OGL-UK-3.0 -->

## Introduction

This repository is maintained by three designated maintainers (the **IES Top Maintenance Team**), each bringing distinct expertise to ensure that IES Top meets cross-government requirements, is ontologically rigorous, and is soundly implemented in RDF. A separate security contact handles vulnerability disclosures.

All three maintainers share collective responsibility for:
1. Reviewing and responding to issues raised on this repo
2. Assessing documentation updates and corrections
3. Where applicable, overseeing updates developed by approved contributors
4. Reviewing pull requests and overseeing the repository

In addition to the above, their individual roles reflect areas of lead responsibility, not exclusive ownership. Maintainer roles are filled from, and at the direction of, the IES Technical Group (TG), which in turn reports to the IES Steering Group (SG).

---

## Maintainer Roles

### Cross-Government Representative

Ensures that all changes align with cross-government requirements and the strategic objectives of the Information Exchange Standard initiative. Moreover, ensures compliance with licensing and security practices.

### Foundational Ontology SME

Ensures the conceptual quality, correctness, and consistency of the top ontology and its documentation as well as its adherence to accepted standards for 4-dimensional, extensional foundational ontology.

### RDF Ontology Implementation Maintainer

Ensures the quality, correctness, and consistency of the RDF serialisation of the top ontology.

---

## Current IES Top Maintenance Team

| Name | Organisation | Contact |
| ---- | ------------ | ------- |
| Nigel D | HM Government | https://github.com/nigel81562 |
| Chris P | BORO Solutions Ltd | https://github.com/chrispartridge1091 |
| Andreas C | Telicent Ltd | https://github.com/afizzycola |

---

### Security Contact

A separate security contact is responsible for receiving and coordinating vulnerability reports. For the current security contact and the responsible disclosure process, see [SECURITY.md](SECURITY.md).

For general issues, please **open a GitHub issue** rather than contacting maintainers directly.

---

## Repository Access

Access to the ies-top repository is controlled as follows:

- **Write access** is limited to IES-Org members only.
- **Maintain access** is limited to the three members of the IES Top Maintenance Team listed above.
- **Admin access** is held by the Cross-Government Representative, in addition to their Maintain access.

---

## Review and Approval Process

All issues and proposed changes are reviewed by the appropriate maintainers. No change may be merged into `main` or released without their **unanimous agreement**.

---

## Development Process

Changes to this repository follow a structured development process based on the nature of the change.

### Ontological Changes

Changes to the conceptual structure of the ies-top ontology are led by the **Foundational Ontology SME** and developed in a conceptual **UML model**, with support from the other two maintainers. The UML model serves as the conceptual reference for the ies-top ontology's structure.

### RDF Ontology Implementation Changes

Changes to the RDF serialisation are led by the **RDF Ontology Implementation Maintainer** and developed in a **UML-ODM model**, which is then serialised into RDF, with support from the other two maintainers. The RDF Ontology Implementation should be traceable back to the conceptual UML model. Where the RDF diverges from the UML model due to implementation constraints, these divergences must be documented and justified.

### Governance, Documentation, and Repository Changes

Changes that are neither ontological nor RDF-specific (e.g. governance documents, repository structure, supporting documentation) are allocated to the maintainers as is appropriate for the change. Any changes relating to governance must first be recommended by the IES Technical Group and then approved by the IES Steering Group before associated changes are made by the maintainers.

---

## Escalation Contacts

If you need to escalate an issue that has not been addressed within a reasonable time:

1. **Security vulnerabilities** – Follow the responsible disclosure process in [SECURITY.md](SECURITY.md).
2. **Governance and policy queries** – Contact DBT at [IES@businessandtrade.gov.uk](mailto:IES@businessandtrade.gov.uk?subject=IES%20GitHub%20Request%20-%20re%3A%20IES-TOP&body=Please%20provide%20detailed%20information%20about%20your%20request%2C%20including%3A%0D%0A-%20A%20clear%20description%20of%20the%20issue%20or%20query.%0D%0A-%20Relevant%20context%20or%20background.%0D%0A-%20Any%20supporting%20documentation%20or%20links.%0D%0A%0D%0A%3C%3CDetails%20of%20your%20request%20or%20concern%3E%3E).
3. **Urgent operational issues** – Contact any of the maintainers listed above.

---

## Updating this File

Maintainer details may change over time. If you are an authorised maintainer and need to update this file, please request changes through the IES GitHub administrators via [IES@businessandtrade.gov.uk](mailto:IES@businessandtrade.gov.uk?subject=IES%20GitHub%20Request%20-%20re%3A%20IES-TOP&body=Please%20provide%20detailed%20information%20about%20your%20request%2C%20including%3A%0D%0A-%20A%20clear%20description%20of%20the%20issue%20or%20query.%0D%0A-%20Relevant%20context%20or%20background.%0D%0A-%20Any%20supporting%20documentation%20or%20links.%0D%0A%0D%0A%3C%3CDetails%20of%20your%20request%20or%20concern%3E%3E).

---

**Maintained as part of the Information Exchange Standard initiative.**

© Crown Copyright 2026. This work is currently under the custodianship of the Department for Business and Trade (UK), acting on behalf of a cross-government group of stakeholders.
Licensed under the Open Government Licence v3.0.

For full licensing terms, see [OGL_LICENSE.md](OGL_LICENSE.md).
