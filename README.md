# TypeScript Project Template

A flexible, modern TypeScript project template ready for any use case.

## Features

- ✨ **Modern TypeScript** – Latest version with strict mode enabled
- 📦 **ESLint & Prettier** – Code quality and formatting configured
- 🎣 **Git Hooks** – Husky + lint-staged for automated checks
- 🚀 **GitHub Workflows** – CI/CD pipelines for testing and releases
- 📝 **Documentation** – MIT license, contributing guide, and more
- 🔧 **VSCode Ready** – Recommended extensions and debugging setup
- 🤖 **Dependabot** – Automatic dependency updates

## Quick Start

### Prerequisites

- Node.js 18+ (see `.nvmrc`)
- pnpm 9+ (or npm/yarn)

### Setup

```bash
# Install dependencies
pnpm install

# Verify setup
pnpm type-check
pnpm lint
pnpm build
```

## Available Scripts

- `pnpm build` – Build the project
- `pnpm lint` – Run ESLint
- `pnpm lint:fix` – Fix linting issues
- `pnpm format` – Format code with Prettier
- `pnpm format:check` – Check formatting without changes
- `pnpm type-check` – TypeScript type checking

## Project Structure

```
.
├── src/              # Source code
├── tests/            # Test files
├── dist/             # Build output
├── .github/          # GitHub workflows & templates
├── .vscode/          # VSCode configuration
├── package.json
├── tsconfig.json
├── eslint.config.js
├── .prettierrc
└── README.md
```

## Configuration

- **TypeScript:** [tsconfig.json](tsconfig.json)
- **ESLint:** [eslint.config.js](eslint.config.js)
- **Prettier:** [.prettierrc](.prettierrc)
- **Git Hooks:** [.lintstagedrc.json](.lintstagedrc.json)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT – See [LICENSE](LICENSE) for details.
