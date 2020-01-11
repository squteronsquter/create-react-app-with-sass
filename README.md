# This is how you add Sass support to your react app bootstrapped with create-react-app --template typescript

## Install typescript globally if you have not done so yet

### `sudo npm install -g typescript`

## Then create react app as you woul dnormally do with create-react-app

### `npx create-react-app@latest my-react-ts-app --template typescript

### `cd my-react-ts-app`

### `yarn add node-sass`

## Change all the css files and import references to .scss

## Create Sass code for your styles as you would normally do in any Sass project

### `yarn build`

### `yarn global add serve`

### `serve -s build`

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

### Happy coding
