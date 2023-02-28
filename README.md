<h1 align="center">Version Control Assignment</h1>

This repository consists of a project, which uses Nodejs as a backend technology and React as a frontend technology.
____
## Libraries and Framework used

- [Express](https://expressjs.com/) - "Fast, unopinionated, minimalist web framework for Node.js".

- [React](https://reactjs.org/) - "A JavaScript library for building user interfaces".

- [Webpack](https://www.npmjs.com/package/webpack) - A popular tool for building front end assets e.g. CSS and JavaScript.

- [Sucrase](https://www.npmjs.com/package/sucrase) - A simpler and faster alternative to [Babel](https://babeljs.io/) which brings support for JSX, TypeScript, ES modules, and more to your client side and server side JavaScript.

## Requirements

- [Node.js](https://nodejs.org/en/download/) >= v12

## Application structure

- `client/` directory - React front end code.
- `server/` directory - Node.js back end code.
- `static/` directory - Compiled front end assets. Created by webpack when you run the
command `npm run build`. The Node.js back end serves serves these assets using the
[`express.static`](https://expressjs.com/en/starter/static-files.html#serving-static-files-in-express) middleware.

## Usage

```bash
# Install dependencies for front end and back end
npm install

# Build front end assets with webpack
npm run build

# Run Node.js back end server
npm start
```

Load up http://localhost:3000 in your browser to view the example website.



