```
$ npm test

  var _ref = _asyncToGenerator(function* ({ bar }) {});
                                          ^

SyntaxError: Unexpected token {
    at exports.runInThisContext (vm.js:53:16)
    at Module._compile (module.js:373:25)
    at loader (/private/tmp/foo/node_modules/babel-cli/node_modules/babel-register/lib/node.js:144:5)
    at Object.require.extensions.(anonymous function) [as .js] (/private/tmp/foo/node_modules/babel-cli/node_modules/babel-register/lib/node.js:154:7)
    at Module.load (module.js:343:32)
    at Function.Module._load (module.js:300:12)
    at Function.Module.runMain (module.js:441:10)
    at /private/tmp/foo/node_modules/babel-cli/lib/_babel-node.js:159:24
    at Object.<anonymous> (/private/tmp/foo/node_modules/babel-cli/lib/_babel-node.js:160:7)
    at Module._compile (module.js:409:26)
```
