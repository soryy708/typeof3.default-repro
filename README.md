* TypeError: (0 , _typeof3.default) is not a function

1. Clone this repo
2. `npm install`
3. `cd subrepo && npm install && cd ..`
4. `npm test`

Trace:

```
TypeError: (0 , _typeof3.default) is not a function
    at _typeof (C:\Users\soryy\Desktop\repro\subrepo\node_modules\@babel\runtime\helpers/typeof.js:2:39)
    at Object.<anonymous> (C:\Users\soryy\Desktop\repro\subrepo\node_modules\regenerator-runtime/runtime.js:710:3)
    at Module._compile (internal/modules/cjs/loader.js:956:30)
    at Module._compile (C:\Users\soryy\Desktop\repro\node_modules\pirates\lib\index.js:99:24)
    at Module._extensions..js (internal/modules/cjs/loader.js:973:10)
    at Object.newLoader [as .js] (C:\Users\soryy\Desktop\repro\node_modules\pirates\lib\index.js:104:7)
    at Module.load (internal/modules/cjs/loader.js:812:32)
    at Function.Module._load (internal/modules/cjs/loader.js:724:14)
    at Module.require (internal/modules/cjs/loader.js:849:19)
    at require (internal/modules/cjs/helpers.js:74:18)
    at Object.<anonymous> (C:\Users\soryy\Desktop\repro\subrepo\node_modules\@babel\runtime\regenerator/index.js:1:18)
    at Module._compile (internal/modules/cjs/loader.js:956:30)
    at Module._compile (C:\Users\soryy\Desktop\repro\node_modules\pirates\lib\index.js:99:24)
    at Module._extensions..js (internal/modules/cjs/loader.js:973:10)
    at Object.newLoader [as .js] (C:\Users\soryy\Desktop\repro\node_modules\pirates\lib\index.js:104:7)
    at Module.load (internal/modules/cjs/loader.js:812:32)
    at Function.Module._load (internal/modules/cjs/loader.js:724:14)
    at Module.require (internal/modules/cjs/loader.js:849:19)
    at require (internal/modules/cjs/helpers.js:74:18)
    at Object.<anonymous> (C:\Users\soryy\Desktop\repro\subrepo\index.test.js:5:43)
    at Module._compile (internal/modules/cjs/loader.js:956:30)
    at Module._compile (C:\Users\soryy\Desktop\repro\node_modules\pirates\lib\index.js:99:24)
    at Module._extensions..js (internal/modules/cjs/loader.js:973:10)
    at Object.newLoader [as .js] (C:\Users\soryy\Desktop\repro\node_modules\pirates\lib\index.js:104:7)
    at Module.load (internal/modules/cjs/loader.js:812:32)
    at Function.Module._load (internal/modules/cjs/loader.js:724:14)
    at Module.require (internal/modules/cjs/loader.js:849:19)
    at require (internal/modules/cjs/helpers.js:74:18)
    at C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\mocha.js:334:36
    at Array.forEach (<anonymous>)
    at Mocha.loadFiles (C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\mocha.js:331:14)
    at Mocha.run (C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\mocha.js:809:10)
    at Object.exports.singleRun (C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\cli\run-helpers.js:108:16)
    at exports.runMocha (C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\cli\run-helpers.js:142:13)
    at Object.exports.handler (C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\cli\run.js:292:3)
    at Object.runCommand (C:\Users\soryy\Desktop\repro\node_modules\yargs\lib\command.js:242:26)
    at Object.parseArgs [as _parseArgs] (C:\Users\soryy\Desktop\repro\node_modules\yargs\yargs.js:1087:28)
    at Object.parse (C:\Users\soryy\Desktop\repro\node_modules\yargs\yargs.js:566:25)
    at Object.exports.main (C:\Users\soryy\Desktop\repro\node_modules\mocha\lib\cli\cli.js:68:6)
    at Object.<anonymous> (C:\Users\soryy\Desktop\repro\node_modules\mocha\bin\mocha:164:29)
    at Module._compile (internal/modules/cjs/loader.js:956:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:973:10)
    at Module.load (internal/modules/cjs/loader.js:812:32)
    at Function.Module._load (internal/modules/cjs/loader.js:724:14)
    at Function.Module.runMain (internal/modules/cjs/loader.js:1025:10)
    at internal/main/run_main_module.js:17:11
```
