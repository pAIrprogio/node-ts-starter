# Node TS Starter

> A modern Node TS starter project using as many native Node.js features as possible

## Features

- Modern TS config
- Type stripping to run .ts files directly
- Native Node.js test runner
- Uses Yarn through corepack
- Non intrusive ESLint config
- Prettier config
- Full VSCode config

## Scripts

- `yarn test` - Run all tests
- `yarn test:types` - Run type checking
- `yarn test:lint` - Run linting
- `yarn test:unit` - Run unit tests
- `yarn test:e2e` - Run E2E tests

## Notes

- Requires Node.js >= 22.9.0
- Unit tests are suffixed with `.test.ts`
- E2E tests are suffixed with `.e2e.ts`
- If you want to use npm publish, make sure to set `"private": false` in your package.json
