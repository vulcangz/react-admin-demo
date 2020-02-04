# React-admin Demo

This is a demo of the [react-admin](https://github.com/marmelab/react-admin) library for React.js. Fork from [React-admin Demo](https://github.com/vulcangz/react-admin/tree/demo_dev/examples/demo). Separated from react-admin repository. It creates a working administration for a fake poster shop named Posters Galore. You can test it online at http://marmelab.com/react-admin-demo.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

React-admin usually requires a REST/GraphQL server to provide data. In this demo however, the API is simulated by the browser (using [FakeRest](https://github.com/marmelab/FakeRest)). The source data is generated at runtime by a package called [data-generator](https://github.com/marmelab/react-admin/tree/master/examples/data-generator).

To explore the source code, start with [src/App.js](https://github.com/marmelab/react-admin/blob/master/examples/demo/src/App.js).

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## Why

The original [examples/demo](https://github.com/vulcangz/react-admin/tree/demo_dev/examples/demo) requires the react-admin repository to run. After separation, it can be used as a front-end template based on the react + react-redux + react-sega + material-ui + react-admin technology stack.

## How to run

After having cloned this repository, run the following commands at the react-admin root:

```sh
yarn install

yarn build

yarn start
```

## Credits

Thank you to the following **GIANTS**:

* [github.com/facebook/react/](https://github.com/facebook/react/) [Docs](https://zh-hans.reactjs.org/)

* [github.com/marmelab/react-admin](https://github.com/marmelab/react-admin) [Docs](https://marmelab.com/react-admin/Readme.html)

* [github.com/mui-org/material-ui](https://github.com/mui-org/material-ui) [Docs](https://material-ui.com/zh/)

* [github.com/reduxjs/react-redux](https://www.github.com/reduxjs/react-redux) [Docs](https://react-redux.js.org/)

* [github.com/redux-saga/redux-saga](https://github.com/redux-saga/redux-saga) [Docs](https://redux-saga.js.org/)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `npm run deploy`

Deploy the build to GitHub gh-pages.
