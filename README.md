
# Modern Javascript

Following this excellent [tutorial](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70) to nail down the basics of webpack and babel. Eyes toward grunt (or brunch?), but here we are emulating the same results with `package.json` scripts.

## Commands
- To compile the code in `index.js` to a single script:
`./node_modules/.bin/webpack index.js bundle.js`

- Couldn't get it to work before adding config file

- Also prompted us to install `webpack-cli` -- not sure if that was needed

- For babel: `npm install babel-core babel-preset-env babel-loader --save-dev`

- Indeed, we can find the transpiled code in the bundle.js

- To build: `npm run build`

- To watch for saved changes: `npm run watch`

- To run a server: `npm install webpack-dev-server --save-dev`, and then add to config `"server": "webpack-dev-server --open"` -- enables automatic browser reload.
