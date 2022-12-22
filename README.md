# mini-vite

## a simple vite achieve

## mini-vite can do these now
- [x] supports quick start in development
- [x] supports vue sfc
- [x] supports plugins
- [x] adding hrm....
### UseAge
#### build.js
```js
//you can see example to see a simply use 
//dev.js use this file to run dev for your program
const { createServer } = require('../dist/index.cjs') //import dev server
const viteConfig = require('./vite.config') // import vite config
createServer(viteConfig)  //start dev server
```
#### start
```shell
> node .\dev.js
vite start at : http://localhost:3000
request asserts => / status: 200
request asserts => /src/main.js status: 200
request asserts => /src/vue.esm-bundler.js status: 200
request asserts => /@modules/vue status: 200
request asserts => /src/App.vue status: 200
request asserts => /@modules/@vue/runtime-dom status: 200
request asserts => /src/App.vue status: 200
request asserts => /@modules/@vue/shared status: 200
request asserts => /@modules/@vue/runtime-core status: 200
request asserts => /@modules/@vue/reactivity status: 200
request asserts => /src/vue.esm-bundler.js.map status: 404
```
