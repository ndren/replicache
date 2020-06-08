# repc

This is a Rust port of [replicache-client](https://github.com/rocicorp/replicache-client).

# Initial Goals

The initial strategy is to move fast and get all the way through to a drop-in replacement to replicache-client as quickly as possible.

Things that don't matter for this initial pass:

 * Optimizing, at all (as long as we think the general approach can be optimized)
 * Clients other than https://github.com/rocicorp/replicache-sdk-js
 * Environments other than wasm
 * Idiomatic-ness (we are learning Rust at same time, so removing this from worry list will make us go waaaay faster)

Things that do matter:

 * Continuous tests
 * Basic Perf Benchmarks (just so we know where we are, espec relative to Go)
 * Monitoring of WASM bundle size
