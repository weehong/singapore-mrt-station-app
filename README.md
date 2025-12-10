# Singapore MRT Station App

A TypeScript library and dataset for Singapore MRT (Mass Rapid Transit) stations, providing comprehensive information about the Singapore rail network.

## Features

- 📊 Complete dataset of Singapore MRT stations
- 🚇 Support for all MRT lines (North-South, East-West, Circle, Downtown, Thomson-East Coast, etc.)
- 🔍 Interactive CLI for exploring station information
- 📦 Type-safe TypeScript implementation
- 🧪 Fully tested with Jest
- 📚 Well-documented API

## Installation

```bash
npm install singapore-mrt-station-app
```

## Usage

```typescript
import { /* your exports */ } from 'singapore-mrt-station-app';

// Example usage will be added as the library develops
```

### CLI Usage

```bash
npm start
```

## Development

### Prerequisites

- Node.js >= 18.0.0
- npm or yarn

### Setup

```bash
# Clone the repository
git clone https://github.com/weehong/singapore-mrt-station-app.git
cd singapore-mrt-station-app

# Install dependencies
npm install

# Build the project
npm run build
```

### Available Scripts

- `npm start` - Run the built application
- `npm run build` - Compile TypeScript to JavaScript
- `npm run dev` - Watch mode for development
- `npm run lint` - Lint the codebase
- `npm run lint:fix` - Fix linting issues automatically
- `npm run format` - Format code with Prettier
- `npm run format:check` - Check code formatting
- `npm test` - Run tests
- `npm run test:watch` - Run tests in watch mode
- `npm run test:coverage` - Generate test coverage report

## Project Structure

```text
singapore-mrt-station-app/
├── src/               # Source files
│   └── index.ts       # Main entry point
├── dist/              # Compiled output
├── .husky/            # Git hooks
├── package.json       # Project metadata
├── tsconfig.json      # TypeScript configuration
├── eslint.config.js   # ESLint configuration
├── jest.config.js     # Jest configuration
└── README.md          # Project documentation
```

## Code Quality

This project uses:

- **TypeScript** - Static type checking
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Jest** - Unit testing
- **Husky** - Git hooks for pre-commit and pre-push checks
- **Commitlint** - Conventional commit message enforcement

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/amazing-feature`)
3. Commit your changes using conventional commits (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feat/amazing-feature`)
5. Open a Pull Request

### Commit Convention

This project follows [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, etc.)
- `refactor:` - Code refactoring
- `test:` - Adding or updating tests
- `chore:` - Maintenance tasks

## License

MIT © Vernon

## Acknowledgments

- Data sourced from Land Transport Authority (LTA) Singapore
- Inspired by the need for accessible Singapore MRT station information

## Contact

- Author: Vernon
- Repository: [weehong/singapore-mrt-station-app](https://github.com/weehong/singapore-mrt-station-app)

---

Made with ❤️ in Singapore
