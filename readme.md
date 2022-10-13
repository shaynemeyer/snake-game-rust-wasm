# Snake Game Rust and wasm

Simple version of the classic snake game written in Rust, WebAssembly, TypeScript, and JavaScript.

## Install wasm-pack

```bash
cargo install wasm-pack
```

## Compiling Rust to WASM

Make sure you have the `wasm-pack` installed and good to go. Once you have that from the root directory, build for wasm with the following command:

```bash
wasm-pack build --target web
```

## Running dev

With webpack installed, you can run the following command:

```bash
cd www
npm install
npm run dev
```

## Dependencies

### npm

- [express](https://expressjs.com/)
- [compression](https://github.com/expressjs/compression#readme)
- [copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin)
- [webpack](https://www.npmjs.com/package/webpack)
- [webpack-cli](https://github.com/webpack/webpack-cli/tree/master/packages/webpack-cli)
- [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server)

### Rust

- [installing rust](https://www.rust-lang.org/tools/install)
- [wasm-pack](https://rustwasm.github.io/docs/wasm-pack/) - makes working with webassembly and rust very simple.

## Resources

- <https://en.wikipedia.org/wiki/Snake_(video_game_genre)>
- <https://webassembly.org/>
- <https://rustwasm.github.io/book/>
- <https://rustwasm.github.io/docs/book/>
- <https://developer.mozilla.org/en-US/docs/WebAssembly>
- <https://webassembly.github.io/wabt/demo/wat2wasm/>

### VSCode Extensions

- <https://marketplace.visualstudio.com/items?itemName=dtsvet.vscode-wasm>
- <https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer>
- <https://marketplace.visualstudio.com/publishers/rust-lang>
