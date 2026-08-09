# Contribution Guidelines

**Repository:** `IES Top Ontology (ies-top)`    
**Description:** `Guidelines for issue reporting, documentation suggestions, and the IES controlled contribution model.`

<!-- SPDX-License-Identifier: OGL-UK-3.0 -->

Thank you for your interest in this repository. The IES Top ontology, grounded in well-established literature on Extensionalism and 4-Dimensionalism, is expected to evolve gradually. Most users of IES will find that their requests-for-change are applicable to ies-core or to domain-specific, lower-level modules. Accordingly, changes to this top-level ontology are anticipated only in exceptional circumstances - such as when new requirements necessitate additional foundational ontology grounding, or when there are substantive developments in the conceptual landscape.

The Information Exchange Standard (IES) is developed and maintained as a cross-government initiative with contributions from various UK government organisations and technical support from approved suppliers and subject matter specialists.

The Department for Business and Trade (DBT) is the current custodian of this repository and the GitHub organisation, acting on behalf of a broader group of stakeholders.

IES follows an **open-source governance model**, where all code is **publicly available** under open-source licences, and collaboration is invited from **approved contributors**. While direct code contributions from the general public are not currently accepted, we **welcome feedback, issue reporting, and documentation suggestions**.

To see a list of contributing organisations and individuals, refer to [ACKNOWLEDGEMENTS.md](ACKNOWLEDGEMENTS.md) and the GitHub contributor insights page at [Contributors](https://github.com/IES-Org/ies-top/graphs/contributors).

---

## How You Can Contribute

Public users and contributors are encouraged to engage in the following ways:

- **Reporting bugs and issues** – If you find a problem, please open a GitHub issue.
- **Suggesting documentation improvements** – Propose clarifications or additions to existing documentation.
- **Providing structured feedback** – Use GitHub Issues to share ideas and enhancement suggestions.

All input is welcome and will be reviewed by maintainers, but prioritisation is subject to IES goals and delivery timelines.

At this time, IES does not accept **public pull requests (PRs)** or **direct code contributions**. Contributions are limited to **approved government contributors and suppliers** working under formal arrangements.
For contact details, refer to [MAINTAINERS.md](MAINTAINERS.md).

---
## How Changes Are Developed

This repository is maintained by three designated maintainers (the **IES Top Maintenance Team**) with complementary expertise. All proposed changes are reviewed by the appropriate maintainers, and **no change may be merged or released without their unanimous agreement**.

The development process depends on the nature of the change:

- **Ontological changes** to the conceptual structure of the top ontology are led by the Foundational Ontology SME and developed in a UML model, with support from the other two maintainers.
- **RDF Ontology Implementation changes** are led by the RDF Ontology Implementation Maintainer and developed in RDF, with support from the other two maintainers. The RDF Ontology Implementation should be traceable to the UML model; any divergences due to implementation constraints are documented and justified.
- **Governance, documentation, and repository changes** are allocated to the maintainers as is appropriate for the change. Any changes relating to governance must first be recommended by the IES Technical Group (TG) and then approved by the IES Steering Group (SG) before associated changes are made by the maintainers.

For full details of the maintainer roles and development process, see [MAINTAINERS.md](MAINTAINERS.md).

---

## Reporting Issues

If you encounter a bug, error, or inconsistency, please follow these steps:

1. Check for an existing issue under [Issues](https://github.com/IES-Org/ies-top/issues).
2. Open a new issue if none exists. Use one of the available templates.
3. Provide a clear and detailed description, including steps to reproduce if applicable.
4. Use labels (bug, documentation, enhancement, etc.) where appropriate.

For security-related concerns, do not submit a public issue. Follow our [Responsible Disclosure process](SECURITY.md).

---

## Documentation Feedback

If you find an error, need clarification, or have suggestions for improving documentation:

1. Open a GitHub issue using the `documentation` label.
2. Describe the suggestion clearly, referencing specific content where possible.
3. Structured, specific feedback helps us respond more effectively.

Documentation updates are prioritised based on user impact and strategic relevance.

---

## Issue Resolution Workflow

Once an issue has been raised, the IES Top Maintenance Team will follow this process:

1. The issue is categorised (e.g. bug, enhancement, modelling question, clarification).
2. The team determines whether the issue affects ies-top or shall be addressed in ies-core or a lower-level domain module.
3. If development to ies-top is warranted, the team undertakes a model-driven approach with regular updates posted against the associated GitHub issue.
4. Once the team reaches an agreed approach, one member of IES Top Maintenance Team raises a pull request.
5. The remaining two maintainers act as the primary reviewers.
6. Only after the pull request has been approved by the remaining two maintainers, can the pull request be merged into `main`.

### Minimum Review Period

New issues on this repo must have an initial response provided by either member of the IES Top Maintenance Team within 4 weeks of the ticket being created. This:

- Gives contributors time to comment.
- Prevents proposals being escalated the day they are published.
- Improves the quality of technical discussion.
- Avoids rushed or uninformed decision-making.

Additionally, pull requests that propose changes to governance (e.g. contribution policies, maintainer roles, decision-making processes) must remain open for a minimum of 4 weeks to allow for comment from stakeholders. For the approval process governing such changes, see [How Changes Are Developed](#how-changes-are-developed).

---

## IES Approach to Open-Source Development

- **All code is published under open-source licences.**
- **Development is led by contributors from government and approved suppliers.**
- **Feedback is welcome and helps shape ongoing development.**

---


## Contribution Licensing

By submitting feedback, documentation suggestions, or issue reports, you acknowledge that any resulting contributions will be licensed under the same terms as this repository:

- Code (if applicable) is licensed under the **MIT License**.
- Documentation is licensed under the **Open Government Licence v3.0 (OGL v3.0)**.

All contributions are considered Crown copyright.

---

## Repository Maintainers

For current maintainers and contact information, refer to [MAINTAINERS.md](MAINTAINERS.md).
Maintainers review issues, guide contributions, and ensure alignment with programme objectives.

---

**Maintained as part of the Information Exchange Standard initiative.**

© Crown Copyright 2026. This work is currently under the custodianship of the Department for Business and Trade (UK), acting on behalf of a cross-government group of stakeholders.
Licensed under the Open Government Licence v3.0.

For full licensing terms, see [OGL_LICENSE.md](OGL_LICENSE.md).
