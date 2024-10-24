# @types/jison

TypeScript Definitions for the Jison Parser Generator

## Description
This package provides TypeScript type definitions for the popular [Jison](https://github.com/zaach/jison) parser generator. With these type definitions, developers can leverage TypeScript's static typing to work more effectively with Jison-generated parsers.

## Features
- Accurate type definitions for Jison.
- Provides better autocompletion and error-checking in TypeScript projects.
- Compatible with Jison v0.3.0 and higher.

## Installation
```bash
npm install @types/jison

```

## Usage

After installing the package, simply import Jison as you normally would. TypeScript will automatically use the provided type definitions to improve the development experience

```typescript

import { Parser } from 'jison';

// Example usage
const parser = new Parser(grammar);

```
## Contributing

If you find any issues or have suggestions for improvement, please feel free to create an issue or submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details