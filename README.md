# hello-wasm-c

https://wasmbyexample.dev/examples/hello-world/hello-world.c.en-us.html

```shell
git clone https://github.com/emscripten-core/emsdk.git
cd emsdk
./emsdk install latest
./emsdk activate latest
source ./emsdk_env.sh
```

```shell
emcc life.cpp -o life.js
emcc life.cpp -o3 -o life.html
```

https://albertoimpl.com/hello-wasm-c/hello/hello.html
https://albertoimpl.com/hello-wasm-c/life/life.html