# A Yarn Workspaces + Webpack + React Starter Kit 🔰

This is a simple starter kit for those who want to use **Yarn Workspaces** and **Webpack**.

The starter kit is also also configured to use **React**.

## Pre-requisites

- Node.js 10.15.0
- Yarn 1.13.0

## Environment variables

- `NODE_ENV` eg. `production`
- `PORT` eg. `8080`

## Scripts

For development:

- `cd ./packages/package-app`
- `yarn start`

For production:

- `cd ./packages/package-app`
- `yarn build`

## What's in the box

- [Yarn Workspaces](https://yarnpkg.com/lang/en/docs/workspaces/)
- [Webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [PostCSS](https://postcss.org/)
- [React](https://reactjs.org/)

### JavaScript

- [babel-loader](https://github.com/babel/babel-loader)
- [@babel/preset-env](https://babeljs.io/docs/en/babel-preset-env)
- [@babel/preset-react](https://babeljs.io/docs/en/babel-preset-react)
- [@babel/plugin-syntax-dynamic-import](https://babeljs.io/docs/en/babel-plugin-syntax-dynamic-import)
- [@babel/polyfill](https://babeljs.io/docs/en/babel-polyfill)
- [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin)

### CSS

- [style-loader](https://github.com/webpack-contrib/style-loader)
- [css-loader](https://github.com/webpack-contrib/css-loader)
- [postcss-loader](https://github.com/postcss/postcss-loader)
- [poscess-preset-env](https://github.com/csstools/postcss-preset-env)
- [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin)
- [optimize-css-assets-webpack-plugin](https://github.com/NMFR/optimize-css-assets-webpack-plugin)

### HTML

- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin)
