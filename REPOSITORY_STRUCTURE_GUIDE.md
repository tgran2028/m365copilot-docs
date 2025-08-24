# Repository Structure and Key Documents by Directory

This document organizes key documents by their location in the repository structure.

## Root Level (/)

### Essential Files
- **[README.md](README.md)** - Repository overview and contributing info
- **[CONTRIBUTING.md](CONTRIBUTING.md)** - Detailed contribution guidelines

### Configuration Files
- **[.markdownlint.json](.markdownlint.json)** - Markdown linting rules
- **[cspell.json](cspell.json)** - Spell checking configuration
- **[.openpublishing.publish.config.json](.openpublishing.publish.config.json)** - Publishing configuration

### Security & Legal
- **[SECURITY.md](SECURITY.md)** - Security issue reporting
- **[LICENSE](LICENSE)** - Repository license
- **[ThirdPartyNotices.md](ThirdPartyNotices.md)** - Third-party attribution

## docs/ (Main Documentation)

### 🏆 Primary Entry Points
- **[index.md](docs/index.md)** - Main landing page
- **[planning-guide.md](docs/planning-guide.md)** - Strategic planning guide
- **[agents-overview.md](docs/agents-overview.md)** - Core agent concepts

### 📋 Site Structure
- **[TOC.yml](docs/TOC.yml)** - Complete site navigation
- **[docfx.json](docs/docfx.json)** - DocFX build configuration
- **[context.yml](docs/context.yml)** - Context configuration

### 🚀 Getting Started
- **[prerequisites.md](docs/prerequisites.md)** - Development environment setup
- **[samples.md](docs/samples.md)** - Code samples collection
- **[cost-considerations.md](docs/cost-considerations.md)** - Cost planning

### 🤖 Declarative Agents
- **[overview-declarative-agent.md](docs/overview-declarative-agent.md)** - Overview
- **[build-declarative-agents.md](docs/build-declarative-agents.md)** - Building guide
- **[declarative-agent-tool-comparison.md](docs/declarative-agent-tool-comparison.md)** - Tool comparison

#### Schema References
- **[declarative-agent-manifest-1.5.md](docs/declarative-agent-manifest-1.5.md)** - Latest (v1.5)
- **[declarative-agent-manifest-1.4.md](docs/declarative-agent-manifest-1.4.md)** - v1.4
- **[declarative-agent-manifest-1.3.md](docs/declarative-agent-manifest-1.3.md)** - v1.3
- **[declarative-agent-manifest-1.2.md](docs/declarative-agent-manifest-1.2.md)** - v1.2
- **[declarative-agent-manifest-1.0.md](docs/declarative-agent-manifest-1.0.md)** - v1.0

### 🔌 API Plugins
- **[overview-api-plugins.md](docs/overview-api-plugins.md)** - Overview
- **[build-api-plugins-new-api.md](docs/build-api-plugins-new-api.md)** - New API guide
- **[build-api-plugins-existing-api.md](docs/build-api-plugins-existing-api.md)** - Existing API guide

#### Schema References
- **[api-plugin-manifest-2.3.md](docs/api-plugin-manifest-2.3.md)** - Latest (v2.3)
- **[api-plugin-manifest-2.2.md](docs/api-plugin-manifest-2.2.md)** - v2.2
- **[api-plugin-manifest-2.1.md](docs/api-plugin-manifest-2.1.md)** - v2.1

### 🏗️ Custom Engine Agents
- **[overview-custom-engine-agent.md](docs/overview-custom-engine-agent.md)** - Overview
- **[m365-agents-sdk.md](docs/m365-agents-sdk.md)** - Microsoft 365 Agents SDK
- **[teams-ai-library.md](docs/teams-ai-library.md)** - Teams AI Library

### 🔗 Copilot Connectors
- **[overview-copilot-connector.md](docs/overview-copilot-connector.md)** - Overview
- **[build-your-first-connector.md](docs/build-your-first-connector.md)** - Tutorial
- **[build-connectors-with-people-data.md](docs/build-connectors-with-people-data.md)** - People data

### 🎨 Copilot Studio
- **[copilot-studio-agent-builder.md](docs/copilot-studio-agent-builder.md)** - Overview
- **[copilot-studio-agent-builder-build.md](docs/copilot-studio-agent-builder-build.md)** - Building
- **[agent-builder-templates.md](docs/agent-builder-templates.md)** - Templates

### 🔧 APIs & Services
- **[copilot-apis-overview.md](docs/copilot-apis-overview.md)** - APIs overview
- **[orchestrator.md](docs/orchestrator.md)** - Copilot orchestrator

### 🛠️ Development Support
- **[debugging-copilot-agent.md](docs/debugging-copilot-agent.md)** - Testing/debugging
- **[declarative-agent-instructions.md](docs/declarative-agent-instructions.md)** - Writing instructions
- **[localize-agents.md](docs/localize-agents.md)** - Localization

### 📋 Support & Reference
- **[faq.md](docs/faq.md)** - Frequently asked questions
- **[known-issues.md](docs/known-issues.md)** - Known issues
- **[feedback.md](docs/feedback.md)** - Support channels

## docs/api/ (API Reference)

### Core API Documentation
- **[README.md](docs/api/README.md)** - API documentation overview
- **[toc.yml](docs/api/toc.yml)** - API navigation structure

### AI Services APIs
- **[docs/api/ai-services/retrieval/overview.md](docs/api/ai-services/retrieval/overview.md)** - Retrieval API overview

### Structured API Reference
```
docs/api/
├── admin-settings/           # Admin configuration APIs
├── ai-services/
│   ├── change-notifications/ # Change notification APIs
│   ├── interaction-export/   # Interaction export APIs
│   ├── meeting-insights/     # Meeting insights APIs
│   └── retrieval/           # Retrieval APIs
└── resources/               # Common resource definitions
```

## docs/includes/ (Reusable Content)

### Sample Manifests
- **[sample-manifests/](docs/includes/sample-manifests/)** - All sample manifest files
  - declarative-agent-sample-manifest-1.5.json (Latest)
  - plugin-sample-manifest-2.3.json (Latest)

### Shared Content
- Various include files for reusable content snippets

## docs/assets/ (Supporting Files)

### Images
- **[images/](docs/assets/images/)** - All documentation images

### Scripts
- **[scripts/GetSharePointIds.ps1](docs/assets/scripts/GetSharePointIds.ps1)** - SharePoint ID retrieval utility

### Code Snippets
- **[snippets/](docs/assets/snippets/)** - Code examples and API samples

## scripts/ (Repository Maintenance)

### Utility Scripts
- PowerShell scripts for repository maintenance and validation

## Directory Navigation Tips

### Starting Points by Directory
- **Root**: README.md for repository info
- **docs/**: index.md for platform overview
- **docs/api/**: API reference and technical specs
- **docs/includes/**: Sample manifests and reusable content

### Most Important Files by Directory
1. **Root**: README.md, .markdownlint.json, cspell.json
2. **docs/**: index.md, TOC.yml, planning-guide.md
3. **docs/api/**: overview documents for each service
4. **docs/includes/sample-manifests/**: Latest manifest samples

This structure-based view helps you navigate the repository systematically and understand where different types of content are located.