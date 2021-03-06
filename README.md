# expect-exception.fail

> Official Website of [expect(Exception)](https://www.expect-exception.fail/).

This is a fork of the [Sapper + TailwindCSS Rollup template](https://github.com/Vannsl/sapper-tailwindcss-template).

## Getting started

1. Make sure you're up and running node v8+ (but just use v12+)
2. Run `npm install` or `yarn install`

## Usage

Run the project and the tailwind watcheer in development mode with:

```bash
npm run dev
```

and in another window of the terminal:

```bash
npm run dev:tailwindcss
```

Open up [localhost:3000](http://localhost:3000).

## Production mode and deployment

Run the project in production mode with:

```bash
npm run build && npm start
```

This application is deployed on [Now](https://zeit.co/now). The project will automatically be redeployed by pushing on the master branch. If you need access to the Now Team, contact [Vannsl](mailto:boehner.vanessa@gmail.com).

To change settings, run:

```bash
npm install -g now
now
```

## Test

This project contains [Cypress](https://www.cypress.io/) tests. To prevent bloating up the node modules, cypress is not a dev dependency. Install it globally with `npm install -g cypress`. To run the tests, execute

```bash
npm run test
```
