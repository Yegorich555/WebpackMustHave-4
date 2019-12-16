# WebpackMustHave

## Info

Webpack version: 4.41.3

## How to run project

1. Open project in VSCode (for example)
2. Run command `npm i` in terminal (console) for installing all required packages (Node.js is required: <https://nodejs.org/en/>)
3. For builing project you can use the following commands:
   - `npm run build-prod` - building production version (minimized and optimized). The project will be builded into `build` folder. You can change destination in `webpack.common.js (line 19)`
   - `npm run build-dev` - building development version
   - `npm run serve` - building development hot-reloaded version with webpack-dev-server

## Recommended VSCode extensions

- CSS Modules: <https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules>
- CSS Modules Syntax Highlighter: <https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-css-modules>
- ESlint: <https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint>
- Stylelint: <https://marketplace.visualstudio.com/items?itemName=thibaudcolas.stylelint>
- SCSS intellisense: <https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss>
- Path intellisense: <https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense>
- Prettier - Code formatter: <https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode>
- Import Cost: <https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost>

## TODO

- add webpack-mock-server (with hot-replacement and ts-support)
- fix peek-to-definition (for none-js-files)
- replace Prettier by better alternative (Prettier works bad)
- update style-loader when hot-replacemnet for css-modules will be fixed
- simplify config for webpack.styles when css-loader will be updated: <https://github.com/webpack-contrib/css-loader/issues/994>
- add icomoon to fonts
- find solution for .browserslistrs and stylelint integration
