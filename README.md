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

3. Extend this config in your `.eslintrc` file

```json
{
  "extends": [
    "brandoniffert"
  ]
}
```
