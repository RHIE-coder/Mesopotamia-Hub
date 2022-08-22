# Env Setting

## React

```sh
npm install react react-dom 
```

## Babel

```sh
npm install -D @babel/cli @babel/core @babel/preset-env @babel/preset-react
```
 - `@babel/preset-env` : for compiling ES2015+ syntax


## Webpack

```sh
npm install -D webpack webpack-cli babel-loader
```
 - `babel-loader` : ES6 --> ES5

## hello world

```js
import React from 'react';
import ReactDOM from 'react-dom/client';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<h1>Hello, world!</h1>);
```