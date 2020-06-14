# toolchain

### ESLint
#### Linter
Uses the **airbnb** config and **typescript-eslint** to establish ruleset. Along with the main **ESLint** package, this project uses a number of other ESLint-related packages:
- **@typescript-eslint/eslint-plugin** - ESLint plugin that provides rules for TypeScript.
- **@typescript-eslint/parser** - Allows TypeScript to be parsed for ESLint.
- **eslint-config-airbnb** - Popular ESLint config that works well with React.
- **eslint-plugin-import** - Allows ESLint to properly lint ES Modules.
- **eslint-plugin-jsx-a11y** - Allows ESLint to check accessibility of JSX elements.
- **eslint-plugin-react** - ESLint plugin that provides React-specific linting rules for ESLint.
- **eslint-plugin-react-hooks** - ESLint plugin that provides linting rules for React hooks.

### Node
#### Runtime Environment
Node modules like `path` are used during development, like during **Webpack** bundling. A few other Node-related packages are used:
- **@types/node** to add Node types for TypeScript.
- **ts-loader** to allow Webpack to read and parse TypeScript.
- **ts-node** allows `node` to be executed in tandem with `tsc`.

### React
#### Front-End Framework

### TypeScript
#### Typed Superset of JavaScript

### Webpack
#### Bundler

