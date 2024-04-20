# Carbon React with Node.js

React is a popular framework for creating user interfaces in modular components. In this sample application, you will create a web application using Express and React to serve web pages in Node.js, complete with standard best practices, including a health check and application metric monitoring.

This app contains an opinionated set of components for modern web development, including:

* [React](https://facebook.github.io/react/)
* [Sass](http://sass-lang.com/) 
* [Carbon](https://www.carbondesignsystem.com/)
* [Create React App](https://github.com/facebook/create-react-app)

#### Native Application Development

Install the latest [Node.js](https://nodejs.org/en/download/) 6+ LTS version.

Once the Node toolchain has been installed, you can download the project dependencies with:

```bash
npm install -g yarn
yarn install
```

##### Local development

To run application for local development and get live updates on code changes:

```sh
yarn start:dev
```

##### Test

To run unit tests:

```sh
yarn test
```

##### Run production build

To try a production build, run:

```sh
yarn build
yarn start
```
