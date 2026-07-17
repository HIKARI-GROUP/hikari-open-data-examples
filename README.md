<div align="center">

# 🏔️ HIKARI Open Data Examples

**Exemples d'utilisation de données immobilières publiques françaises — DVF, DPE, cadastre**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE) [![JavaScript](https://img.shields.io/badge/JavaScript-blue)]() [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![Leaflet](https://img.shields.io/badge/Leaflet-199900?logo=leaflet&logoColor=white)](https://leafletjs.com/) [![Data Visualization](https://img.shields.io/badge/Data_Visualization-blue)]()
[![Version](https://img.shields.io/badge/version-v0.1.0-blue)](./CHANGELOG.md)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()
[![Coverage](https://img.shields.io/badge/coverage-90%25-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/HIKARI-GROUP/hikari-open-data-examples)](https://github.com/HIKARI-GROUP/hikari-open-data-examples)
[![Last Commit](https://img.shields.io/github/last-commit/HIKARI-GROUP/hikari-open-data-examples)](https://github.com/HIKARI-GROUP/hikari-open-data-examples/commits)
[![Discussions](https://img.shields.io/github/discussions/HIKARI-GROUP/hikari-open-data-examples)](https://github.com/HIKARI-GROUP/hikari-open-data-examples/discussions)

[📖 Documentation](./docs/) · [🗺️ Roadmap](./ROADMAP.md) · [🤝 Contributing](./CONTRIBUTING.md) · [💻 Examples](./examples/) · [🧪 Tests](./tests/) · [🤖 AI](./ai/) · [💼 Careers](./CAREERS.md)

</div>

---

## 📋 Overview

Example code and visualizations using French public real estate data sources: DVF (Demandes de Valeurs Foncières), DPE (energy performance), cadastre, and INSEE demographics.

## ✨ Features

- 🏠 DVF transaction data fetching
- 🔋 DPE energy performance lookup
- 🗺️ Interactive Leaflet maps
- 📊 Price per m² visualization
- 📈 Market trend charts
- 🏘️ Neighborhood analysis
- 🔍 Anonymized synthetic datasets

## 🏗️ Architecture

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

## 🚀 Installation

```bash
git clone https://github.com/HIKARI-GROUP/hikari-open-data-examples.git
```

## 📖 Usage

```javascript
import { fetchDvfByPostalCode } from "./dvf";

const sales = await fetchDvfByPostalCode("69001", 2024);
console.log(sales); // [{ price, surface, date, type, ... }]
```

## 📁 Project Structure

```
hikari-open-data-examples/
├── examples/
│   ├── dvf-by-postal-code.js
│   ├── dvf-map/
│   └── dpe-lookup.js
├── src/
│   ├── dvf.ts           # DVF API client
│   ├── dpe.ts           # DPE utilities
│   └── cadastre.ts      # Cadastre data
├── datasets/            # Synthetic sample data
└── docs/
```

## 🛠️ Technologies

- JavaScript
- TypeScript
- Leaflet
- Data Visualization

## 📚 Documentation

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

## 🗺️ Roadmap

See [ROADMAP.md](./ROADMAP.md) for our full vision.

## 🤝 Contributing

We welcome contributions! Please read [CONTRIBUTING.md](./CONTRIBUTING.md) first.

- 🐛 [Report a bug](https://github.com/HIKARI-GROUP/hikari-open-data-examples/issues/new?labels=bug)
- 💡 [Request a feature](https://github.com/HIKARI-GROUP/hikari-open-data-examples/issues/new?labels=enhancement)
- 📝 [Improve docs](https://github.com/HIKARI-GROUP/hikari-open-data-examples/issues/new?labels=documentation)
- 🔍 [Good first issues](https://github.com/HIKARI-GROUP/hikari-open-data-examples/labels/good%20first%20issue)

## 📄 License

MIT © HIKARI GROUP

## 💼 Careers

We're hiring! See [CAREERS.md](./CAREERS.md) for open positions.

## 🌐 Links

- 🏢 [HIKARI GROUP](https://github.com/HIKARI-GROUP)
- 🌍 [Website](https://hikari-group.com)
- 💼 [LinkedIn](https://www.linkedin.com/company/hikari-group)
- 📧 [Contact](mailto:contact@hikari-group.com)

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/HIKARI-GROUP">HIKARI GROUP</a></sub>
</div>
