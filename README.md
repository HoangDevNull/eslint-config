# @hdn/eslint-next-config

This package provides an ESLint configuration tailored for Next.js projects, integrating both Prettier and Tailwind CSS. Ensure that [Prettier](https://prettier.io/) and [Tailwindcss](https://tailwindcss.com/) are installed in your project before proceeding.

## Installation

```shell
npm install -D @hdn/eslint-next-config
```

This command installs the package along with all necessary peer dependencies.

## Configuration

After installation, set up the ESLint configuration by creating a file named .eslintrc.js in the root directory of your Next.js project. Populate this file with the following code to extend the ESLint rules from this package:

```js
module.exports = {
  extends: ["@hdn/eslint-next-config"],
};
```

This setup will incorporate the custom ESLint rules provided by @hdn/eslint-next-config into your project, enabling a consistent coding style that leverages the best practices of Next.js, Prettier, and Tailwind CSS.
