# Zinn One ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### Default (JavaScript/TypeScript)

Para projetos JavaScript ou TypeScript básicos:

Install dependencies:
```bash
npm i -D eslint @zinnone/eslint-config
```

Inside `.eslintrc.json`:
```json
{
  "extends": "@zinnone/eslint-config"
}
```

### React (with Next.js)

Install dependencies:
```bash
npm i -D eslint @zinnone/eslint-config
```

Inside `.eslintrc.json`:
```json
{
  "extends": [
    "@zinnone/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```bash
npm i -D eslint @zinnone/eslint-config
```

Inside `.eslintrc.json`:
```json
{
  "extends": "@zinnone/eslint-config/react"
}
```

### Node.js

Install dependencies:
```bash
npm i -D eslint @zinnone/eslint-config
```

Inside `.eslintrc.json`:
```json
{
  "extends": "@zinnone/eslint-config/node"
}
```

## Available Configurations

- **Default** (`@zinnone/eslint-config`): Base configuration for JavaScript/TypeScript projects
- **React** (`@zinnone/eslint-config/react`): React projects without Next.js
- **Next.js** (`@zinnone/eslint-config/next`): Next.js projects  
- **Node.js** (`@zinnone/eslint-config/node`): Node.js backend projects
