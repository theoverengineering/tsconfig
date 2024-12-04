# TS Config &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![npm version](https://img.shields.io/npm/v/@theoverengineering/tsconfig.svg?style=flat)](https://www.npmjs.com/package/@theoverengineering/tsconfig) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)

A TypeScript configuration optimized for modern development environments.

## Features

This package provides a single tsconfig file with recommended settings:

- Type Checking: Enables strict type checking options like noImplicitAny, strict, noUnusedLocals, etc.
- Modules: Uses ESNext module and Bundler module resolution.
- Interop Constraints: Enables esModuleInterop and verbatimModuleSyntax.
- Language and Environment: Targets ESNext version of JavaScript.

## Installation

Install the package using npm:

```sh
npm install @theoverengineering/tsconfig
```

## Usage

Extend your project's `tsconfig.json` with the provided configuration:

```json
{
  "extends": "@theoverengineering/tsconfig"
}
```

This will include the compiler options defined in the package, which are designed for strict type checking and modern module resolution.

## Contributing

We welcome contributions! Please see our [contributing guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Project status

This project is actively maintained. If you have any questions or need help, feel free to open an issue.
