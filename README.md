# @excalidraw/eslint-config

Excalidraw's [ESLint](https://eslint.org/docs/developer-guide/shareable-configs) config.

## Usage for CRA

### Install (macOS, Linux)

```bash
yarn add --dev @excalidraw/eslint-config \
               @typescript-eslint/eslint-plugin \
               @typescript-eslint/parser \
               @babel/eslint-parser \
               eslint-config-prettier \
               eslint-plugin-flowtype \
               eslint-plugin-import \
               eslint-plugin-jsx-a11y \
               eslint-plugin-prettier \
               eslint-plugin-react \
               eslint-plugin-react-hooks \
               prettier
```

### Edit `.eslintrc.json`

```jsonc
{
  // ...
  "extends": "@excalidraw/eslint-config"
}
```
