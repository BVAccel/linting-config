# BVA Linting Configuration

Baseline configs that should be used across all BVA projects. More to come here. Instructions on installing and configuring. 

## Configurations

Setup default configurations for all your projects by copying over `.eslintrc`, `.eslintignore`, `.prettierrc` and `.stylelintrc` in `/Users/your-username` directory. Local configuration files will take precedence over the global configs.

## Dependencies

These should be installed globally on your machine, to be used across all projects:


```
npm i -g stylelint
npm i -g eslint
npm i -g prettier
npm i -g -D stylelint-scss
npm i -g -D stylelint-order
npm i -g -D eslint-config-airbnb
npm i -g -D eslint-config-prettier
npm i -g -D eslint-config-airbnb
npm i -g -D eslint-config-airbnb-base
npm i -g -D eslint-plugin-prettier
npm i -g -D eslint-plugin-import 
npm i -g -D eslint-plugin-jsx-a11y 
npm i -g -D eslint-plugin-react 
npm i -g -D eslint-plugin-prettier 
```

Single line installation:

```
npm i -g stylelint eslint prettier && npm i -g -D stylelint-scss stylelint-order eslint-config-airbnb eslint-config-prettier eslint-config-airbnb eslint-config-airbnb-base eslint-plugin-prettier eslint-plugin-import  eslint-plugin-jsx-a11y  eslint-plugin-react  eslint-plugin-prettier 
```

## Text Editor Plugins

### VSCode

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [Prettier](https://github.com/prettier/prettier-vscode)
* [Stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)

### Sublime

* [ESLint](https://github.com/SublimeLinter/SublimeLinter-eslint)
* [Prettier](https://packagecontrol.io/packages/JsPrettier
)
* [Stylelint](https://github.com/SublimeLinter/SublimeLinter-stylelint)
