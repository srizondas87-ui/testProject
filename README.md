# firstproject

Node.js starter. CommonJS, with [dotenv](https://github.com/motdotla/dotenv) for environment variables. There is no application entry file yet; `package.json` points `main` at `index.js`.

## Requirements

- Node.js 18 or newer

## Setup

```bash
npm install
```

Create a `.env` file in the project root for local secrets. Do not commit it.

```text
EXAMPLE_KEY=value
```

Load it from application code:

```js
require("dotenv").config();

const value = process.env.EXAMPLE_KEY;
```

## Scripts

```bash
npm test
```

`npm test` is still the default npm placeholder and exits with an error until a test runner is added.

## Layout

```text
firstproject/
  package.json
  package-lock.json
  cursor.md
  README.md
```
