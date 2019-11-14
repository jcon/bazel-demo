# TypeScript Project References Demo

This repository showcases a TS monorepo uses yarn workspaces + TypeScript project
references to efficiently build only what's needed.

## Usage

To setup the project run:

```bash
yarn
```

To build the project:

```bash
yarn build:cli
```

Execute the produced bundle:
```bash
node ./packages/cli/dist/test.js
```

## License

MIT

