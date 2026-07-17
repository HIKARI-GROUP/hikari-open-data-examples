<div align="center">

# ðï¸ HIKARI Open Data Examples

**Exemples d'utilisation de donnÃ©es immobiliÃ¨res publiques franÃ§aises â DVF, DPE, cadastre**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE) [![JavaScript](https://img.shields.io/badge/JavaScript-blue)]() [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![Leaflet](https://img.shields.io/badge/Leaflet-199900?logo=leaflet&logoColor=white)](https://leafletjs.com/) [![Data Visualization](https://img.shields.io/badge/Data_Visualization-blue)]()
[![Version](https://img.shields.io/badge/version-v0.1.0-blue)](./CHANGELOG.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/HIKARI-GROUP/hikari-open-data-examples)](https://github.com/HIKARI-GROUP/hikari-open-data-examples)
[![Last Commit](https://img.shields.io/github/last-commit/HIKARI-GROUP/hikari-open-data-examples)](https://github.com/HIKARI-GROUP/hikari-open-data-examples/commits)
[![Discussions](https://img.shields.io/github/discussions/HIKARI-GROUP/hikari-open-data-examples)](https://github.com/HIKARI-GROUP/hikari-open-data-examples/discussions)

[ð Documentation](./docs/) Â· [ðºï¸ Roadmap](./ROADMAP.md) Â· [ð¤ Contributing](./CONTRIBUTING.md) Â· [ð» Examples](./examples/) Â· [ð§ª Tests](./tests/) Â· [ð¤ AI](./ai/) Â· [ð¼ Careers](./CAREERS.md)

</div>

---

## ð Overview

Example code and visualizations using French public real estate data sources: DVF (Demandes de Valeurs FonciÃ¨res), DPE (energy performance), cadastre, and INSEE demographics.

## â¨ Features

- ð  DVF transaction data fetching
- ð DPE energy performance lookup
- ðºï¸ Interactive Leaflet maps
- ð Price per mÂ² visualization
- ð Market trend charts
- ðï¸ Neighborhood analysis
- ð Anonymized synthetic datasets

## ðï¸ Architecture

```mermaid
graph TD
    subgraph "HIKARI HIKARI Open Data Examples"
        A[Frontend] --> B[Backend]
        B --> C[Database]
        B --> D[Integrations]
        B --> E[AI/LLM]
    end
```

See [Architecture](./docs/Architecture.md) for full details.

## ð Installation

```bash
git clone https://github.com/HIKARI-GROUP/hikari-open-data-examples.git
```

## ð Usage

```javascript
import { fetchDvfByPostalCode } from "./dvf";

const sales = await fetchDvfByPostalCode("69001", 2024);
console.log(sales); // [{ price, surface, date, type, ... }]
```

## ð Project Structure

```
hikari-open-data-examples/
âââ examples/
â   âââ dvf-by-postal-code.js
â   âââ dvf-map/
â   âââ dpe-lookup.js
âââ src/
â   âââ dvf.ts           # DVF API client
â   âââ dpe.ts           # DPE utilities
â   âââ cadastre.ts      # Cadastre data
âââ datasets/            # Synthetic sample data
âââ docs/
```

## ð ï¸ Technologies

- JavaScript
- TypeScript
- Leaflet
- Data Visualization

## ð Documentation

| Document | Description |
|---|---|
| [Architecture](./docs/Architecture.md) | System architecture and design decisions |
| [Backend](./docs/Backend.md) | Backend services and API |
| [Frontend](./docs/Frontend.md) | Frontend architecture |
| [Database](./docs/Database.md) | Database schema and operations |
| [API](./docs/API.md) | API conventions |
| [Authentication](./docs/Authentication.md) | Auth flows |
| [Security](./docs/Security.md) | Security practices |
| [Deployment](./docs/Deployment.md) | Deployment guide |
| [Coding Standards](./docs/Coding-Standards.md) | Code conventions |
| [Testing](./docs/Testing.md) | Testing guide |
| [CI-CD](./docs/CI-CD.md) | CI/CD pipeline |
| [Git Workflow](./docs/Git-Workflow.md) | Branching & PR process |
| [Onboarding](./docs/Developer-Onboarding.md) | Developer onboarding |
| [Environment](./docs/Environment.md) | Environment setup |

## ðºï¸ Roadmap

See [ROADMAP.md](./ROADMAP.md) for our full vision.

## ð¤ Contributing

We welcome contributions! Please read [CONTRIBUTING.md](./CONTRIBUTING.md) first.

- ð [Report a bug](https://github.com/HIKARI-GROUP/hikari-open-data-examples/issues/new?labels=bug)
- ð¡ [Request a feature](https://github.com/HIKARI-GROUP/hikari-open-data-examples/issues/new?labels=enhancement)
- ð [Improve docs](https://github.com/HIKARI-GROUP/hikari-open-data-examples/issues/new?labels=documentation)
- ð [Good first issues](https://github.com/HIKARI-GROUP/hikari-open-data-examples/labels/good%20first%20issue)

## ð License

MIT Â© HIKARI GROUP

## ð¼ Careers

We're hiring! See [CAREERS.md](./CAREERS.md) for open positions.

## ð Links

- ð¢ [HIKARI GROUP](https://github.com/HIKARI-GROUP)
- ð [Website](https://hikari-group.tech)
- ð¼ [LinkedIn](https://www.linkedin.com/company/hikari-group)
- ð§ [Contact](mailto:contact@hikari-group.tech)

---

<div align="center">
  <sub>Built with â¤ï¸ by <a href="https://github.com/HIKARI-GROUP">HIKARI GROUP</a></sub>
</div>
