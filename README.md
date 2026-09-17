# Customer Support Copilot — Azure Architecture Governance

An [ArcKit](https://arckit.org/)-style architecture governance demonstration project: a curated set of AI-assisted governance artifacts for an **AI-powered, retrieval-augmented customer support copilot on Azure**, for a fictional mid-size SaaS company.

📖 **[View the documentation site](https://harishsubash.github.io/arckit-usecase-azure-support-copilot/)**

## Use Case

The company is augmenting its human support team with a RAG-based copilot — Azure OpenAI Service, Azure AI Search, Azure Functions, Cosmos DB, Blob Storage, API Management, and Microsoft Entra ID — that grounds every answer in the knowledge base and hands off to a human agent whenever confidence is low.

## What's in Here

This repo follows the ArcKit convention of one governance artifact per architectural concern, versioned and cross-referenced:

| Artifact | Description |
|----------|-------------|
| Architecture Principles | Foundational decisions that constrain every downstream choice |
| Stakeholder Analysis | Who cares about this platform and how they're engaged |
| Requirements | Functional and non-functional requirements, MoSCoW-prioritised |
| Risk Register | Identified risks, likelihood/impact scoring, mitigations |
| Business Case | Strategic, economic, commercial, financial and management case |
| Architecture Strategy | Target state and phased rollout approach |
| Platform Design | Service-level design with architecture and sequence diagrams |
| Architecture Decision Records | Key technology choices with rationale and alternatives considered |

Browse them all in the [documentation site](https://harishsubash.github.io/arckit-usecase-azure-support-copilot/), or read the source markdown under [`projects/`](projects/).

## About This Project

This is a **demonstration/portfolio project**, not a real client deliverable. The fictional company, its numbers, and its stakeholders are illustrative. All artifacts were drafted with AI assistance (Claude) and reviewed by [Harish Subash](https://github.com/harishsubash) — always validate AI-generated architecture output with human expertise before using it for real decisions.

The documentation viewer (`docs/index.html`) is reused from the MIT-licensed [ArcKit](https://github.com/tractorjuice/arc-kit) project — see [NOTICE.md](NOTICE.md) for attribution.

## License

MIT — see [LICENSE](LICENSE).
