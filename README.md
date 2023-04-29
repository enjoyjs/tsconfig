# tsconfig

Shared TypeScript config for @enjoyjs projects

## Highlights

- Enable recommended options
- Strict type checking
- Configuration for modern web development

For details of the configuration, see [here](tsconfig.json).

## Install

```bash
npm i -D @enjoyjs/tsconfig
```

_This config requires TypeScript 5.0 or later._

## Usage

`tsconfig.json`

```json
{
  "extends": "@enjoyjs/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```
