# @excalidraw/eslint-config

Excalidraw's [ESLint](https://eslint.org/docs/developer-guide/shareable-configs) config.

## Usage for CRA

### Install (macOS, Linux)

```bash
yarn add --dev @excalidraw/eslint-config \
               @typescript-eslint/eslint-plugin \
               @typescript-eslint/parser \
               eslint-config-prettier \
               eslint-plugin-prettier
               prettier
```

### Edit `.eslintrc.json`

```jsonc
{
  // ...
  "extends": "@excalidraw/eslint-config"
}
```
