# What am I building

- This react web application is the frontend for my commodities data backend application build with Python/Django found here: https://github.com/emmanueluwa/commodities_trading

- I will be starting the frontend react using a webpack and babel setup to keep the tools limited for optimisation and simplicity.

## Things I have learnt whilst working on this webapp:

- Webpack
  https://webpack.js.org/configuration/dev-server/

- ECMAScript is just a standard for scripting languages one of which is javascript. It is used to ensure(interoperability) that the web pages are functional on different web browsers
  https://en.wikipedia.org/wiki/ECMAScript

- React is a root that the entire app gets mounted on

- - public/index.html

- - - this file does not need to change

- - the index file runs and the bundle (App.js) that is rewritten again and again is linked to it

- I am also starting with a small nodejs http server(inside webpack.config.js):

```
devServer: {
static: {
directory: path.join(\_\_dirname, "public"),
},
compress: true,
port: 3000,
},
```
