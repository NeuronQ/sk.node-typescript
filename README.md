# Project X

`TODO: intro`

## How to run

### Setup

```shell
npm install
npm run build # if built code is not in git
node ./dists/index.js
```

## How to develop

Setup:

```shell
npm install
npm run prepare # sets up pre-commit hooks etc.
```

Build:

```shell
npm run build
```

Run built JS:

```shell
npm run start-js
```

Run TS directly with ts-node:

```shell
npm run start-ts
```

## How to run tests

```shell
npm test
```

Uses [Jest](https://jestjs.io/) and [ts-jest](https://kulshekhar.github.io/ts-jest/) for testing - just write tests in TS as eg. `tests/something.test.ts` and follow Jest docs.

See:

- https://jestjs.io/docs/getting-started
- https://jestjs.io/docs/using-matchers

To check coverage:

```shell
npm run test-coverage
```

## How to deploy

`TODO`

## How to run

`TODO`

## Alternatives

- https://github.com/microsoft/TypeScript-Node-Starter
  - fat starter kit including express, mongodb connectivity etc.
