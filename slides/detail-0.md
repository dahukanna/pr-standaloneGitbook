##  Detailed steps summary
To create the contents of this repository.

* Create Node Project `package.json` file, using `npm init`.
* Update `package.json` with gitbook dependencies and npm scripts.
* Run `npm install --save`, to install a package and save it as a dependency in the `package.json` file.
 * `npm i gitbook-cli gitbook-plugin-prism --save`
 * `npm i rimraf --save` 
* Create gitbook `npm run docs:build`.
* Open gitbook by changing to `_book` directory and open `index.html`. 