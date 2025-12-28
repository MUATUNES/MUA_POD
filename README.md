# MUA_POD

MUA_POD

## Development

This project uses [Trunk.io](https://trunk.io) for code quality, linting, and formatting.

### Prerequisites

- Node.js and npm

### Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run linters and formatters:
   ```bash
   npm run lint    # Run all configured linters
   npm run fmt     # Format code
   ```

### Available Tools

Trunk is configured with the following tools:
- **actionlint**: GitHub Actions workflow linter
- **gitleaks**: Detect hardcoded secrets
- **markdownlint**: Markdown linter
- **prettier**: Code formatter
- **shellcheck**: Shell script linter
- **shfmt**: Shell script formatter
- **trivy**: Security vulnerability scanner
- **trufflehog**: Secret scanner
- **yamllint**: YAML linter

