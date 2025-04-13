# TypeScript Package Starter

A modern, well-configured starter template for creating TypeScript npm packages. This template provides a solid foundation with best practices and essential tooling for TypeScript package development.

## Features

- 📦 **TypeScript Support**: Write your code in TypeScript with proper type checking
- 🧪 **Testing**: Jest configuration for unit testing
- 📝 **Code Quality**: ESLint and Prettier for code linting and formatting
- 🔄 **Git Hooks**: Husky for pre-commit hooks and lint-staged for running linters on staged files
- 📦 **Modern Build**: Microbundle for creating modern JavaScript bundles
- 🔄 **Automated Updates**: Renovate for automated dependency updates
- 📝 **Conventional Commits**: Commitizen for standardized commit messages
- 🛡️ **Strict Version Control**: Enforced Node.js and npm version requirements

## Prerequisites

### Required

- Node.js >= 18.0.0 (LTS recommended)
- npm >= 8.0.0

> **Note**: These version requirements are strictly enforced. The package will not install if your Node.js or npm versions don't meet these requirements.

### Recommended

- Git >= 2.13.0
- An IDE with TypeScript support (VS Code, WebStorm, etc.)

### Why These Versions?

#### Node.js 18+

- Long Term Support (LTS) status
- Modern JavaScript features support
- Built-in fetch API
- Enhanced security features
- Better performance

#### npm 8+

- Improved dependency resolution
- Enhanced security features
- Workspace support
- Better peer dependency handling

## Getting Started

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/imgarylai/ts-package-starter.git
   cd ts-package-starter
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start developing:
   ```bash
   npm run dev
   ```

## Available Scripts

- `npm run build` - Build the package using microbundle
- `npm run dev` - Watch mode for development
- `npm run lint` - Run ESLint
- `npm test` - Run tests
- `npm run prepare` - Install git hooks

## Project Structure

```
.
├── src/               # Source code
│   ├── index.ts      # Main entry point
│   └── index.test.ts # Tests
├── .github/          # GitHub configuration
├── .husky/           # Git hooks
├── dist/             # Built files (generated)
└── node_modules/     # Dependencies
```

## Development Workflow

1. Write your code in the `src` directory
2. Write tests in `*.test.ts` files
3. Run tests with `npm test`
4. Build your package with `npm run build`

## Publishing

1. Update the version in `package.json`
2. Build the package: `npm run build`
3. Publish to npm: `npm publish`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Gary Lai - [@imgarylai](https://github.com/imgarylai)

## Acknowledgments

- [microbundle](https://github.com/developit/microbundle) for the build tooling
- [TypeScript](https://www.typescriptlang.org/) for the programming language
- [Jest](https://jestjs.io/) for testing
- [ESLint](https://eslint.org/) for linting
- [Prettier](https://prettier.io/) for code formatting
- [Husky](https://typicode.github.io/husky/) for git hooks
- [Renovate](https://renovatebot.com/) for dependency updates
