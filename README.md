# npm-package-starter

[![CI](https://github.com/nokazn/tsconfigx/actions/workflows/static-check.yml/badge.svg)](https://github.com/nokazn/tsconfigx/actions/workflows/static-check.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Starter for publishing a NPM package.

## Usage

```bash
# install dependencies
$ yarn # or npm i

# format by Prettier
$ yarn format

# run ESLint
$ yarn lint

# run ESLint, and fix correctable errors
$ yarn lint

# run tests
$ yarn test

# run tests for CI
$ yarn test:ci

# build for CommonJS style
$ yarn build:cjs

# build for ESModule style
$ yarn build:esm
```

You need to set `NPM_TOKEN` in GitHub Secrets for publishing a package in GitHub Actions.

## License

MIT
