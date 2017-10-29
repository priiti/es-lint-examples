# ESLINT
## Setup for ESLint in projects with editor

#### In this example Airbnb guide is used

* All the rules can be found from .eslintrc file

* Initiate package.json file:\
  ` npm init -y `
* Installation:\
  ` npm i -D eslint@4.9.0 `
* Plugins needed:\
  ` npm i -D eslint-config-airbnb@16.1.0 eslint-plugin-import@2.7.0 eslint-plugin-react@7.4.0 eslint-plugin-jsx-a11y@6.0.1 `
* Make sure ESLint plugin is installed in VSCode
* Check for extra rules if needed
* For React JSX add following rule: \
 ` "react/jsx-filename-extension": [1, { "extensions": [".js", ".jsx"] }] `