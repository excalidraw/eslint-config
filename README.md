# @excalidraw/eslint-config

Excalidraw's [ESLint](https://eslint.org/docs/developer-guide/shareable-configs) config.

## Usage for CRA

### Install (macOS, Linux)

```bash
yarn add --dev @excalidraw/eslint-config \
               eslint-config-prettier \
               eslint-plugin-prettier \
               prettier
```

### Install (Windows)

```bash
yarn add --dev @excalidraw/eslint-config ^
               eslint-config-prettier ^
               eslint-plugin-prettier ^
               prettier
```

## Usage for non-CRA

### Install (macOS, Linux)

```bash
yarn add --dev @excalidraw/eslint-config \
               @typescript-eslint/parser \
               @typescript-eslint/eslint-plugin \
               eslint-config-prettier \
               eslint-plugin-prettier \
               eslint \
               prettier
```

### Install (Windows)

```bash
yarn add --dev @excalidraw/eslint-config ^
               @typescript-eslint/parser ^
               @typescript-eslint/eslint-plugin ^
               eslint-config-prettier ^
               eslint-plugin-prettier ^
               eslint ^
               prettier
```

### Edit `.eslintrc.json`

```jsonc
{
  // ...
  "extends": "@excalidraw/eslint-config"
}
```
