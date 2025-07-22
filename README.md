# go-feature-flag/wasm-releases

This repository provides WebAssembly (WASM) releases for the [GO Feature Flag](https://gofeatureflag.org/) project.

## What is GO Feature Flag?

GO Feature Flag is a simple, lightweight, and 100% open-source self-hosted feature flag solution. It enables modifying system behavior without code changes, facilitating faster, lower-risk, and scalable feature releases. Initially Go-centric, it now supports multiple languages via the [OpenFeature](https://openfeature.dev/) standard and a "relay proxy" API server, making it a versatile tool for production feature management.

## Purpose of this Repository

This repository hosts WebAssembly (WASM) builds of GO Feature Flag components. WASM enables high-performance Go-based logic execution in the different OpenFeature servers providers.
While the main `go-feature-flag` repository holds the core Go source, this `wasm-releases` repository offers compiled WASM binaries for easy integration into WebAssembly projects.

## Usage

The `wasm` and `wasi` files are used inside the different providers provided by GO Feature Flag.  
This repository is loaded as a GIT submodule in the different repositories where the provider is built.

## Contribution

Contributions to GO Feature Flag, including its WebAssembly components, are highly welcome! Refer to the [Contributing Guide](https://gofeatureflag.org/docs/contributing) for details.  
Ways to contribute include writing tutorials, improving documentation, submitting bug reports/feature requests, or contributing code. Bi-weekly community meetings are also held; find details on the [GO Feature Flag website](https://gofeatureflag.org/).

## License

This project is MIT licensed. See the `LICENSE` file in the main [go-feature-flag repository](https://github.com/thomaspoignant/go-feature-flag) for details.
