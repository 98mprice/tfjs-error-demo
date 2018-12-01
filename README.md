# tfjs-error-demo

This repo is to demo a bug that happens in the browser but not in a Node enviroment (tested on v10.10.0).

To run the Node.js version:
```
npm install
npm run test
```
You should see a new file `output.png` with a random generated shoe in it.

To run the browser version, open `index.html` in browser, open Chrome dev tools & click the predict button. There should be an error.
