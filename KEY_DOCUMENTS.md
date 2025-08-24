# Key Documents in Microsoft 365 Copilot Extensibility Documentation

This document provides a comprehensive catalog of key documents in the m365copilot-docs repository, organized by category and importance for different audiences.

## Repository Overview

This repository contains 144+ documentation files for Microsoft 365 Copilot extensibility, published to [Microsoft Learn](https://learn.microsoft.com/m365copilot/extensibility).

## Primary Entry Points

### Main Landing Pages
- **[docs/index.md](docs/index.md)** - Primary overview of Microsoft 365 Copilot extensibility
- **[docs/agents-overview.md](docs/agents-overview.md)** - Overview of agents in Microsoft 365 Copilot
- **[docs/planning-guide.md](docs/planning-guide.md)** - Planning guide for building extensions
- **[README.md](README.md)** - Repository information and contribution guidelines

## Core Documentation Categories

### 1. Getting Started & Foundation
- **[docs/prerequisites.md](docs/prerequisites.md)** - Development environment setup
- **[docs/ecosystem.md](docs/ecosystem.md)** - Agents in the Microsoft 365 ecosystem
- **[docs/agents-are-apps.md](docs/agents-are-apps.md)** - Fundamental concept explanation
- **[docs/cost-considerations.md](docs/cost-considerations.md)** - Cost planning and considerations
- **[docs/samples.md](docs/samples.md)** - Collection of sample implementations

### 2. Declarative Agents
#### Core Documentation
- **[docs/overview-declarative-agent.md](docs/overview-declarative-agent.md)** - Declarative agents overview
- **[docs/build-declarative-agents.md](docs/build-declarative-agents.md)** - Main building guide
- **[docs/declarative-agent-tool-comparison.md](docs/declarative-agent-tool-comparison.md)** - Tool selection guide

#### Manifest Reference (Latest to Oldest)
- **[docs/declarative-agent-manifest-1.5.md](docs/declarative-agent-manifest-1.5.md)** - Latest schema (v1.5)
- **[docs/declarative-agent-manifest-1.4.md](docs/declarative-agent-manifest-1.4.md)** - Schema v1.4
- **[docs/declarative-agent-manifest-1.3.md](docs/declarative-agent-manifest-1.3.md)** - Schema v1.3
- **[docs/declarative-agent-manifest-1.2.md](docs/declarative-agent-manifest-1.2.md)** - Schema v1.2
- **[docs/declarative-agent-manifest-1.0.md](docs/declarative-agent-manifest-1.0.md)** - Original schema

#### Advanced Topics
- **[docs/declarative-agent-capabilities-ids.md](docs/declarative-agent-capabilities-ids.md)** - Retrieving capabilities IDs
- **[docs/declarative-agent-instructions.md](docs/declarative-agent-instructions.md)** - Writing effective instructions
- **[docs/declarative-agent-document-interaction.md](docs/declarative-agent-document-interaction.md)** - Document interaction features

### 3. API Plugins
#### Core Documentation
- **[docs/overview-api-plugins.md](docs/overview-api-plugins.md)** - API plugins overview
- **[docs/build-api-plugins-new-api.md](docs/build-api-plugins-new-api.md)** - Building with new APIs
- **[docs/build-api-plugins-existing-api.md](docs/build-api-plugins-existing-api.md)** - Building with existing APIs

#### Manifest Reference (Latest to Oldest)
- **[docs/api-plugin-manifest-2.3.md](docs/api-plugin-manifest-2.3.md)** - Latest API plugin schema
- **[docs/api-plugin-manifest-2.2.md](docs/api-plugin-manifest-2.2.md)** - API plugin schema v2.2
- **[docs/api-plugin-manifest-2.1.md](docs/api-plugin-manifest-2.1.md)** - API plugin schema v2.1

#### Specialized Topics
- **[docs/api-plugin-authentication.md](docs/api-plugin-authentication.md)** - Authentication patterns
- **[docs/api-plugin-adaptive-cards.md](docs/api-plugin-adaptive-cards.md)** - Adaptive card responses
- **[docs/openapi-document-guidance.md](docs/openapi-document-guidance.md)** - OpenAPI specification best practices

### 4. Copilot Studio Agent Builder
- **[docs/copilot-studio-agent-builder.md](docs/copilot-studio-agent-builder.md)** - Main overview
- **[docs/copilot-studio-agent-builder-build.md](docs/copilot-studio-agent-builder-build.md)** - Building agents
- **[docs/copilot-studio-agent-builder-knowledge.md](docs/copilot-studio-agent-builder-knowledge.md)** - Adding knowledge sources
- **[docs/agent-builder-templates.md](docs/agent-builder-templates.md)** - Template overview

### 5. Custom Engine Agents
- **[docs/overview-custom-engine-agent.md](docs/overview-custom-engine-agent.md)** - Custom engine agent overview
- **[docs/m365-agents-sdk.md](docs/m365-agents-sdk.md)** - Microsoft 365 Agents SDK
- **[docs/teams-ai-library.md](docs/teams-ai-library.md)** - Teams AI library approach

### 6. Copilot Connectors
- **[docs/overview-copilot-connector.md](docs/overview-copilot-connector.md)** - Copilot connectors overview
- **[docs/build-your-first-connector.md](docs/build-your-first-connector.md)** - First connector tutorial
- **[docs/build-connectors-with-people-data.md](docs/build-connectors-with-people-data.md)** - People data connectors

### 7. Microsoft 365 Copilot APIs
- **[docs/copilot-apis-overview.md](docs/copilot-apis-overview.md)** - APIs overview
- **[docs/api/ai-services/retrieval/overview.md](docs/api/ai-services/retrieval/overview.md)** - Retrieval API overview

## Configuration & Build Files

### Critical Configuration
- **[docs/TOC.yml](docs/TOC.yml)** - Table of contents structure (navigation)
- **[docs/docfx.json](docs/docfx.json)** - DocFX build configuration
- **[.openpublishing.publish.config.json](.openpublishing.publish.config.json)** - OpenPublishing configuration
- **[.markdownlint.json](.markdownlint.json)** - Markdown linting rules
- **[cspell.json](cspell.json)** - Spell checking configuration

### Sample Manifests
- **[docs/includes/sample-manifests/](docs/includes/sample-manifests/)** - Complete collection of sample manifests
  - Declarative agent manifests (v1.0 through v1.5)
  - API plugin manifests (v2.1 through v2.3)

## Support & Operational Documents

### User Support
- **[docs/faq.md](docs/faq.md)** - Frequently asked questions
- **[docs/known-issues.md](docs/known-issues.md)** - Known issues and limitations
- **[docs/feedback.md](docs/feedback.md)** - Support and feedback channels

### Development & Publishing
- **[docs/debugging-copilot-agent.md](docs/debugging-copilot-agent.md)** - Testing and debugging
- **[docs/publish.md](docs/publish.md)** - Publishing overview
- **[docs/manage.md](docs/manage.md)** - Management overview
- **[CONTRIBUTING.md](CONTRIBUTING.md)** - Contribution guidelines

### Compliance & Security
- **[docs/data-privacy-security.md](docs/data-privacy-security.md)** - Data privacy and security
- **[docs/rai-validation.md](docs/rai-validation.md)** - Responsible AI validation
- **[SECURITY.md](SECURITY.md)** - Security reporting

## Specialized Features Documentation

### Capabilities
- **[docs/knowledge-sources.md](docs/knowledge-sources.md)** - Knowledge sources integration
- **[docs/code-interpreter.md](docs/code-interpreter.md)** - Code interpreter capability
- **[docs/image-generator.md](docs/image-generator.md)** - Image generation capability

### Advanced Topics
- **[docs/optimize-content-retrieval.md](docs/optimize-content-retrieval.md)** - Content retrieval optimization
- **[docs/localize-agents.md](docs/localize-agents.md)** - Localization guide
- **[docs/orchestrator.md](docs/orchestrator.md)** - Copilot orchestrator concepts

## API Reference Documentation

### Core API Areas
- **[docs/api/](docs/api/)** - Complete API reference
  - **Admin Settings**: Copilot admin configuration APIs
  - **AI Services**: Interaction export, meeting insights, retrieval APIs
  - **Change Notifications**: AI interaction change notifications

## Repository Navigation Tips

### For New Developers
1. Start with [docs/index.md](docs/index.md) for overview
2. Review [docs/planning-guide.md](docs/planning-guide.md) for approach
3. Set up environment with [docs/prerequisites.md](docs/prerequisites.md)
4. Choose your path: Declarative agents, Custom engine agents, or Connectors

### For API Reference
- Navigate to [docs/api/](docs/api/) for complete API documentation
- Check [docs/api/toc.yml](docs/api/toc.yml) for API structure

### For Schema References
- Latest declarative agent: [docs/declarative-agent-manifest-1.5.md](docs/declarative-agent-manifest-1.5.md)
- Latest API plugin: [docs/api-plugin-manifest-2.3.md](docs/api-plugin-manifest-2.3.md)

## Document Maintenance

This repository follows Microsoft documentation standards with:
- Markdown linting via `.markdownlint.json`
- Spell checking via `cspell.json`
- OpenPublishing build system
- Automated validation workflows

Total files: 144+ markdown files across 30+ subdirectories.