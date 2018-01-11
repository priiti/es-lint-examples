# ESLINT
## Setup for ESLint in JS projects

#### Airbnb guide is used
https://github.com/airbnb/javascript

* All the rules can be found from .eslintrc file

* Initiate package.json file:

  ` npm init -y `
* Install dependencies:

  ` npm i -D eslint@4.9.0 eslint-config-airbnb@16.1.0 eslint-plugin-import@2.7.0 eslint-plugin-react@7.4.0 eslint-plugin-jsx-a11y@6.0.1 `
* Make sure ESLint plugin is installed in VSCode
* Add extra rules if needed, e.g. .eslintrc file below:
```
{
  "extends": "airbnb",
  "parserOptions": {
    "ecmaVersion": 2017
  },
  "env": {
    "node": true,
    "es6": true,
    "mocha": true
  },
  "rules": {
    "comma-dangle": ["error", "never"],
    "no-unused-vars": [
      "error",
      {
        "vars": "local",
        "args": "none"
      }
    ],
    "no-underscore-dangle": "off",
    "consistent-return": "off",
    "func-names": "off",
    "global-require": "off",
    "react/jsx-filename-extension": [1, { "extensions": [".js", ".jsx"] }]
  }
}
```
