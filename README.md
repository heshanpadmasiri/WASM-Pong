# WASM PONG

Pong implementation in Rust and WebAssembly.

# Build

1. Build wasm

```bash 
$ wasm-pack build
```

2. Build web

```bash

$ cd www && npm install && npm run start
```

After changes to the Rust code, you need to rebuild the wasm package npm will pick up changes automatically.

## Reference

+ [Rust and WebAssembly](https://rustwasm.github.io/docs/book/)
