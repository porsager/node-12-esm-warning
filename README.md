# Node 12.13.1 modules error

Run `node a.js` with Node 12.13.1 to see the error / warning.

```
b
(node:67428) Warning: require() of ES modules is not supported.
require() of .../a.js is an ES module file as it is a .js file whose nearest parent package.json contains "type": "module" which defines all .js files in that package scope as ES modules.
Instead rename a.js to end in .cjs, change the requiring code to use import(), or remove "type": "module" from .../package.json.
```
