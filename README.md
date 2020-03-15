# Eslint and Prettier Setup

## Local / Per Project Install

1. If you don't already have a `package.json` file, create one with `npm init` or `yarn init`

2. In the same directory, run

```
npx install-peerdeps --dev eslint-config-brandoniffert
```
or for yarn

```
npx install-peerdeps --dev --yarn eslint-config-brandoniffert
```

## Global Install

```
npx install-peerdeps --global eslint-config-brandoniffert
```
or for yarn
```
npx install-peerdeps --global --yarn eslint-config-brandoniffert
```

## Usage

Whether you installed locally or globally, you need to extend this config in you local/global `.eslintrc` file

```json
{
  "extends": [
    "brandoniffert"
  ]
}
```
