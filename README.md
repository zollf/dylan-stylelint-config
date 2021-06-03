# Dylan Sass Stylelint Config

Just a index.js config file nothing special. Used to reduce config files and remain consistent throughout projects.

## How to Install
```bash
yarn add --dev https://github.com/zollf/dylan-stylelint-config.git
yarn add --dev stylelint stylelint-config-standard stylelint-scss
```

Add to package.json
```json
"eslintConfig": {
  "extends": "./node_modules/dylan-stylelint-config/index"
},
```

Run Stylelint Test
```bash
yarn run stylelint **/*.scss
```