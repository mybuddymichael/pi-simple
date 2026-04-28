# pi-simple

A bundled Pi extension that combines UI/style customizations into a single extension.

## Install

From npm:

```bash
pi install npm:pi-simple
```

From GitHub:

```bash
pi install git:github.com/mybuddymichael/pi-simple
```

For local development from this directory:

```bash
pi install ./
# or try it for one run only
pi -e ./
```

## Includes

- `assistant-style`
- `startup-header`
- `status-message-style`
- `tool-one-line`
- `user-message-style`

## Excludes

- `handoff`
- `questionnaire`

## Package structure

This package exposes `index.ts` through the `pi.extensions` manifest in `package.json`. Pi core packages are declared as peer dependencies, as required for Pi packages.
