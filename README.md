# TypeScript Package Starter

A modern, well-configured starter template for creating TypeScript npm packages. This template provides a solid foundation with best practices and essential tooling for TypeScript package development.

[![CI](https://github.com/imgarylai/ts-package-starter/actions/workflows/test.yml/badge.svg)](https://github.com/imgarylai/ts-package-starter/actions/workflows/test.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Features

- 📦 Modern build setup with [tsup](https://github.com/egoist/tsup)
- 🔥 ESM and CommonJS support
- 📘 TypeScript with strict mode
- 🧪 Testing with Jest
- 📊 Code coverage reporting
- 📝 API documentation with TypeDoc
- ✨ Code formatting with Prettier
- 🚨 Linting with ESLint
- 🔄 Continuous Integration with GitHub Actions
- 📋 Conventional commits with commitlint
- 🪝 Git hooks with husky
- 🌲 Tree-shakeable exports
- 📦 Optimized npm package exports

## Getting Started

1. Use this template by clicking the "Use this template" button on GitHub
   or clone it directly:

```bash
git clone https://github.com/imgarylai/ts-package-starter.git my-package
cd my-package
```

2. Update the package information:

   - Modify `package.json` with your package name, description, author, etc.
   - Update this README.md with your package's information
   - Update the LICENSE file if needed

3. Install dependencies:

```bash
npm install
```

4. Start developing:

```bash
npm run dev
```

## Example Usage

This is an example of how your package could be used once you publish it. Update this section with your own package's usage:

```typescript
// This is just a placeholder example - replace with your own package's usage
import { YourFunction } from 'your-package-name';

// Use your package
const result = YourFunction();
```

## Development

### Setup

1. Clone the repository:

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

### Available Scripts

- `npm run build` - Build the package with tsup
- `npm run dev` - Watch mode for development
- `npm test` - Run tests
- `npm run test:coverage` - Run tests with coverage
- `npm run lint` - Lint the code
- `npm run type-check` - Check types
- `npm run docs` - Generate documentation
- `npm run docs:watch` - Generate documentation in watch mode
- `npm run clean` - Clean build outputs
- `npm run prepare` - Install git hooks

### Project Structure

```
.
├── src/               # Source code
│   ├── index.ts      # Main entry point
│   └── index.test.ts # Tests
├── .github/          # GitHub configuration
├── .husky/           # Git hooks
├── dist/             # Built files (generated)
├── docs/             # Generated documentation
├── coverage/         # Test coverage reports
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
3. Commit your changes using conventional commits (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Commit Convention

This project uses [Conventional Commits](https://www.conventionalcommits.org/). Examples:

- `feat: add new feature`
- `fix: resolve bug issue`
- `docs: update README`
- `chore: update dependencies`

## Building

The project uses tsup for building, which provides:

- Multiple format outputs (ESM, CommonJS)
- TypeScript declaration files
- Source maps
- Tree shaking
- Minification

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Gary Lai - [@imgarylai](https://github.com/imgarylai)

## Acknowledgments

- [tsup](https://github.com/egoist/tsup) for the amazing build tool
- [TypeScript](https://www.typescriptlang.org/) for the type system
- [Jest](https://jestjs.io/) for testing
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io/) for code formatting
- [Husky](https://typicode.github.io/husky/) for git hooks
