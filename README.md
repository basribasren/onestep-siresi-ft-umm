# onestep-siresi-ft-umm

[![Build Status](https://travis-ci.org/basribasren/boilerplate-react-redux.svg?branch=master)](https://travis-ci.org/basribasren/boilerplate-react-redux) [![Build status](https://ci.appveyor.com/api/projects/status/weuboxr8dwbpp0q2/branch/master?svg=true)](https://ci.appveyor.com/project/basribasren/boilerplate-react-redux/branch/master) [![dependencies Status](https://david-dm.org/basribasren/boilerplate-react-redux/status.svg)](https://david-dm.org/basribasren/boilerplate-react-redux) ![GitHub All Releases](https://img.shields.io/github/downloads/basribasren/boilerplate-react-redux/total.svg) [![GitHub license](https://img.shields.io/github/license/basribasren/boilerplate-react-redux.svg)](https://github.com/basribasren/boilerplate-react-redux/blob/master/LICENSE) [![GitHub last commit](https://img.shields.io/github/last-commit/basribasren/boilerplate-react-redux.svg)](https://github.com/basribasren/boilerplate-react-redux/commits/master)

Sistem Repository Skripsi Fakultas Teknik UMM berbasis PWA. Client-side yang dibangun menggunakan react dan redux.

issue
Missing image:

Launcher icons of the following sizes are required: 48x48, 72x72, 96x96, 144x144, 192x192, 512x512 Platforms affected:android.

Missing image:

An 1024x1024 app icon for the App Store is required Platforms affected:ios.

Missing image:

A launch image of the following sizes is required: 750x1334, 1334x750, 1242x2208, 2208x1242, 640x1136, 640x960, 1536x2048, 2048x1536, 768x1024 and 1024x768 Platforms affected:ios.

## Ecosystem

<!-- prettier-ignore -->
| Project | Status | Description |
|---------|--------|-------------|
| [react]          | [![react-status]][react-package] | A declarative, efficient, and flexible JavaScript library for building user interfaces. |
| [redux]          | [![redux-status]][redux-package] | Predictable state container for JavaScript apps. |

[react]: https://github.com/facebook/react
[react-status]: https://img.shields.io/npm/v/react.svg
[react-package]: https://npmjs.com/package/react
[redux]: https://github.com/reduxjs/redux
[redux-status]: https://img.shields.io/npm/v/redux.svg
[redux-package]: https://npmjs.com/package/redux

## Folder Structure

After creation, your project should look like this:

```
my-app/
├── node_modules/
├── public/
│   └── index.html
│   └── favicon.ico
├── src/
│   └── assets/
│   └── components/
│   └── redux/
│   └── routes/
│   └── variable/
│   └── views/
│   └── app.js
│   └── index.js
│   └── sw.js
├── .babelrc.js
├── .editorconfig
├── .env
├── .eslintignore
├── .eslintrc.js
├── .gitignore
├── .prettierignore
├── .travis.yml
├── .appveyor.yml
├── LICENSE
├── README.md
├── webpack.config.js
├── webpack.config.prod.js
├── package.json

```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `yarn build`

Builds the app for production to the `dist` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

### `yarn serve`

Runs the result of build command with static server.<br>
Firstly, install npm package serve with yarn command `yarn global add serve`.

### Static Server

For environments using [Node](https://nodejs.org/), the easiest way to handle this would be to install [serve](https://github.com/zeit/serve) and let it handle the rest:

```sh
npm install -g serve
serve -s build
```

## Maintainers

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<img src="https://avatars0.githubusercontent.com/u/25193994?v=4" width="100px;"/><br /><sub><b>Basri Basren</b></sub>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Something Missing?

If you have ideas for more “How To” recipes that should be on this page, [let us know](https://github.com/basribasren/boilerplate-react-redux/issues)
