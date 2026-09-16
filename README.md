# TypeScript Template

A minimal Node.js and TypeScript starter with ESLint and Prettier configured.

## Requirements

- Node.js 22 or later
- npm

## Setup

```bash
npm install
```

## VS Code Extensions

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Commands

| Command                     | Description                       |
| --------------------------- | --------------------------------- |
| `npm start`                 | Run `src/index.ts` with ts-node.  |
| `npm run eslint-check-only` | Check the project with ESLint.    |
| `npm run eslint-fix`        | Fix ESLint issues where possible. |
| `npm run prettier`          | Format the project with Prettier. |

## Repository Contents

Keep the configuration files, including `package.json`, `package-lock.json`, `tsconfig.json`, `eslint.config.mts`, Prettier configuration, and `.vscode/`, under version control.

The `.gitignore` excludes `node_modules/`, `src/`, and `dist/` from the template repository.
