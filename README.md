<h1 align="center">Version Control Assignment</h1> 
This repository consists of a project, which uses Nodejs as a backend technology and React as a frontend technology.

___

## Libraries and frameworks used

- [Express](https://expressjs.com/) - "Fast, unopinionated, minimalist web framework for Node.js".

- [React](https://reactjs.org/) - "A JavaScript library for building user interfaces".

- [Webpack](https://www.npmjs.com/package/webpack) - A popular tool for building
front end assets e.g. CSS and JavaScript.

- [Sucrase](https://www.npmjs.com/package/sucrase) - A simpler and faster alternative to [Babel](https://babeljs.io/) which brings support for JSX, TypeScript, ES modules, and more to your client side and server side JavaScript.

## Requirements

- [Node.js](https://nodejs.org/en/download/) >= v12


## Dependencies we will be using:
```
{
  "name": "example-app",
  "scripts": {
    "build": "webpack --mode development --entry ./src/client/index.js --output ./static/bundle.js",
    "start": "node src/server/app.js"
  },
  "dependencies": {
    "express": "^4.17.1"
  },
  "devDependencies": {
    "@sucrase/webpack-loader": "^2.0.0",
    "react": "^16.13.1",
    "react-dom": "^16.13.1",
    "sucrase": "^3.15.0",
    "webpack": "^4.43.0",
    "webpack-cli": "^3.3.12"
  }
}
```
- React frontend dependencies are specified under **devDependencies**
- Nodejs backend dependencies are specified under **dependencies**

## Project structure

```
├── src
│   │
│   ├── client  <- Frontend code resides here
│   │   ├── components
│   │   │   └── ExampleComponent.js  <- Contains code of output shown here
│   │   └── index.js  <- The main entrypoint for your frontend React application
│   │
│   └── server  <- Backend code resides here
│       └── app.js  <- The main entrypoint for your Node.js backend server
│
├── package.json  <- Specifies frontend and backend dependencies
├── package-lock.json
├── README.md
└── webpack.config.js  <- Configuration for compiling frontend assets
```

## Steps to run this project on your machine
1. Install [Node.js](https://nodejs.org/en/download/) on your machine having its version over 12.0.0
To check our node version, run this command on terminal
```
node --version       
```
2. Clone this repository on your machine
```
git clone https://github.com/Jayraj-Malamdi/Version_Control_Assignment.git
```
3. Install dependencies for front end and back end
```
npm install
```
4. Run this code to build front end assets with webpack
```
npm run build
```
5. To run Node.js back end server
```
npm start
```

To view our website we run http://localhost:3030 in our browser.

## Screenshots/Output
![Screenshot from 2023-02-28 15-53-07](https://user-images.githubusercontent.com/122361229/221826309-2e060375-b355-4824-8035-0f0b35e887ce.png)

## Author

[Jayraj-Malamdi](https://github.com/Jayraj-Malamdi)
