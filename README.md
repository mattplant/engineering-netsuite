# Engineering NetSuite

[![Documentation License: CC BY 4.0](https://img.shields.io/badge/Docs_License-CC_BY_4.0-lightgrey.svg?logo=creativecommons)](./LICENSE-DOCS.md)
[![Source Code License: MIT](https://img.shields.io/badge/Source_Code-MIT-blue.svg?logo=open-source-initiative&logoColor=white)](./LICENSE)

> A specification-driven methodology and modern DX pipeline for deterministic, scalable enterprise ERP systems.

This repository explores how to bridge the gap between traditional ERP customization and **modern Software Engineering rigor**. It is an evolving, living document serving as a blueprint for technical leaders and engineers aiming to build scalable greenfield implementations or radically reduce technical debt in existing environments.

## 🏗️ The Foundation: Modern SDLC & Superior DX

Traditional NetSuite development—writing procedural JavaScript directly in the browser or deploying un-linted code via the UI—creates friction, unpredictable bugs, and isolated knowledge silos. You cannot enforce architectural doctrine if the underlying development environment is fragile.

To solve this, I built and maintain the [NetSuite TypeScript SDF Project Template](https://github.com/mattplant/NetSuite-TypeScript-SDF).

This template fundamentally transforms the NetSuite Developer Experience (DX) through:

- **Superior Feedback Loops:** Automated linting (ESLint), formatting (Prettier), and transpilation to SuiteScript 2.1 upon save.
- **Compile-Time Safety:** Leveraging TypeScript and `@hitc/netsuite-types` to catch API errors (e.g., `N/record`, `N/search`) in the IDE rather than at runtime.
- **Infrastructure as Code (IaC):** Defining database schema, fields, and deployments as version-controlled XML via SDF.
- **CI/CD Readiness:** A source-of-truth centered in Git, ready for automated testing (Jest) and deployment pipelines (GitHub Actions).
- **Environment Portability:** Repeatable deployments across Sandbox, Release Preview, and Production without manual UI configuration.

> [!TIP]
> **Getting Started:** View the [template repository](https://github.com/mattplant/NetSuite-TypeScript-SDF) to configure your local environment and connect your first SDF project.

## 🚀 Featured Projects

- **Flagship Project:** [SuiteTools](https://github.com/mattplant/SuiteTools)
  *A high-performance React-based SPA built in TypeScript and deployed to NetSuite via SDF from a monorepo. It serves as the primary proof of concept for the methodologies outlined here.*

## 🙌 Acknowledgments & Attribution

A rising tide lifts all boats. This methodology and the accompanying tools would not be possible without the incredible work of the broader NetSuite developer community. I am firmly standing on the shoulders of giants who paved the way for modern SuiteScript development.

## 👨‍💻 Author

**Matt Plant** | *Senior NetSuite Software Engineer* *Bringing Software Engineering Rigor to the NetSuite Ecosystem.*

- **GitHub:** [@mattplant](https://github.com/mattplant)
- **Web:** [iDev.Systems](https://idev.systems/)

## ⚖️ Legal Disclaimer

This repository is a personal, open-source project and is **not** affiliated with, endorsed by, or sponsored by Oracle Corporation or NetSuite. "Oracle", "NetSuite", "SuiteScript", and "SuiteCloud" are registered trademarks of Oracle Corporation.

Enterprise ERP environments are highly customized; you assume all risk associated with implementing these patterns. Always thoroughly test code in a NetSuite Sandbox prior to Production release.

## 🏷️ License & Attribution

All documentation and diagrams are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Source code and build configurations are licensed under the [MIT License](./LICENSE).

### Attribution Examples

If you reuse this documentation or the architectural diagrams, please provide credit:

> Documentation adapted from [Engineering NetSuite](https://github.com/mattplant/NetSuite-TypeScript-SDF/) by [Matthew Plant](https://idev.systems/), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

**For full license details, please see [LICENSE-DOCS.md](./LICENSE-DOCS.md).**
