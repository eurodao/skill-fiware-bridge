# Skill FIWARE Bridge

[![License: GPL-3.0-only](https://img.shields.io/badge/License-GPL--3.0--only-blue.svg)](LICENSE)
![Status: pre-release](https://img.shields.io/badge/status-pre--release-orange)

A ROS 2 module that publishes skill, task-step and component events from a ROS 2 robot cell to FIWARE Orion-LD as NGSI-LD entities, with open data models for skills and execution traceability.

> **Status:** this repository is being prepared. The first public release, with source code, installation guide and a runnable example, is planned for **June 2027**.

## Related modules

`skill-fiware-bridge` is designed to be used on its own or together with two companion modules:

```mermaid
flowchart LR
    R[skill-recorder] -->|demonstration| S[skill-synthesizer] -->|SkillSpec| B[skill-fiware-bridge] -->|NGSI-LD| F[(FIWARE)]
    style B stroke-width:3px
```

*skill-fiware-bridge can also publish task-step and component events from your own robot application.*

- [skill-recorder](https://github.com/eurodao/skill-recorder)
- [skill-synthesizer](https://github.com/eurodao/skill-synthesizer)

## Features

*To be completed with the first release.*

## Requirements

*To be completed with the first release* (ROS 2 Jazzy on eProsima Vulcanexus; Ubuntu 24.04).

## Installation

*To be completed with the first release.*

## Usage

*To be completed with the first release* — including a minimal "hello world" example and a basic demo.

## Known limitations

*To be completed with the first release.*

## Third-party notices

*To be completed with the first release.*

## Contributing

Issues and suggestions are welcome. Code contributions will be accepted after the first release. Contributors will be asked to sign a Contributor License Agreement that gives euroDAO SAS the right to relicense the contribution under GPL-3.0-only or under a later, more permissive licence.

## License

Copyright © 2026 euroDAO SAS.

Code: [GNU General Public License v3.0 only](LICENSE) (`SPDX-License-Identifier: GPL-3.0-only`).

Data models in `data-models/` are separate works under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (`SPDX-License-Identifier: CC-BY-4.0`).

## Maintainer

**euroDAO SAS**, Montpellier, France · [eurodao.com](https://eurodao.com) · info@eurodao.com

## Acknowledgements

Developed by euroDAO SAS within the MENTOR experiment of the ARISE project, for the ARISE Catalog.

<img src="assets/eu-co-funded.png" alt="Co-funded by the European Union" height="60">&nbsp;&nbsp;<img src="assets/arise-logo.jpg" alt="ARISE project" height="40">

Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or European Commission. Neither the European Union nor the granting authority can be held responsible for them. Co-funded under Horizon Europe Programme of the European Union under Grant Agreement no. 101135784.
