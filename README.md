# Flagsmith SDK WASM Reproduction

## Repro Steps

1. Ensure you have the `wasm32-wasip1` & `wasm32-wasip2` target available
    - `rustup target add wasm32-wasip1`
    - `rustup target add wasm32-wasip2`
2. Attempt to build targeting `wasm32-wasip1`
    - `cargo build --target wasm32-wasip1`
3. Attempt to build targeting `wasm32-wasip2`
    - `cargo build --target wasm32-wasip2`
