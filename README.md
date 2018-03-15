## ESLint Configuration and Setup

A helper repository to demonstrate eslint setup with `npm` and use `wordpress`
config.

For more information, visit [`eslint-config-wordpress`](https://github.com/WordPress-Coding-Standards/eslint-config-wordpress).

### Setup

Clone this repository.

```bash
git clone git@github.com:swashata/eslint-wordpress-test.git
```

Install dependencies.

```bash
npm install
```

### ESLint files

Simply run `npm-script` command. These are predefined in [`package.json`](package.json)
file.

```
npm run-script eslint
npm run-script eslintfix
```

Or if you prefer running from `.bin`

```
node_modules/.bin/eslint *.js
```
