# ESLint config

## Whats included?

- React plugin;
- React Hooks plugin;
- Prettier;
- JSX a11y plugin;
- Import plugin;
- @Typescript-eslint plugin;
- And more!!

### And amazing eslint rules

## Setup

### 1. Install the dependencies

```bash
npm i -D eslint @minozzzi/eslint-config
```

#### or if you use yarn

```bash
yarn add -D eslint @minozzzi/eslint-config
```

#### or if you use pnpm

```bash
pnpm i -D eslint @minozzzi/eslint-config
```

### 2. Create a `.eslintrc.json` file extending the config

```javascript
{
  "extends": "@minozzzi/eslint-config/node"
}
```

OR

```javascript
{
  "extends": "@minozzzi/eslint-config/react"
}
```

OR

```javascript
{
  "extends": "@minozzzi/eslint-config/next"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
