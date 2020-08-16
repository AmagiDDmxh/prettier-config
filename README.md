# @amagi/prettier-config

Provide a common config for projects use

## Installation

```bash
  npm i -D @amagi/prettier-config
```

## Usage

Crate a file named `.prettierrc.js`

```javascript
module.exports = require('@zestia/prettier-config')
```

## Running

As this package only provides the Prettier configuration, it is assumed you already have `prettier` installed in your project.

- It's recommended to install the relevant Editor Addons/Plugins and enable "Pretter on Save".

- It's recommended to add a prettier script to `package.json`. An example one is:

  ```json
  scripts: {
    "prettier": "prettier '**/*.{js,json,css,scss,html,hbs,md}' --write"
  }
  ```

  You can then run the following, to automatically format your project's code:

  ```bash
  npm run prettier
  ```

### References

- https://github.com/zestia/prettier-config
- https://github.com/vuejs/vue/blob/dev/.editorconfig
