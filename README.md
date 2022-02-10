# Starter Kit for Node + Typescript apps - 2022 edition

> **This is basically *the simplest* / *most minimalistic* such starter kit you'll ever find that includes all the basic stuff for serious app development (testing, code quality tools etc.)

Starter kit for apps using:
- Node.js (v16+, probably works with v14 too)
- Typescript
- Jest & ts-jest for testing
- ESLint & typescript-eslint for code-quality checks
- Prettier formatter
- Husky + lint-staged for managing pre-commit hooks and linting staged code (works when staging file chunks too etc.)

## How to run

**NOTE:** See "How to develop" below if you want to actually make changes to the code and not just run the app.

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

Manually run pre-commit checks on staged code:

```shell
npx lint-staged
```

## How to run the tests

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
