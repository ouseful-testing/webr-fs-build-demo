# webr-filesystem-build-demo

Experimenting with building a custom webr wasm file system.

This repo contains an action ([via](https://github.com/r-wasm/actions/tree/main/.github/workflows#r-wasmactions-reusable-workflows)) for creating a [webr Webassembly filesystem](https://docs.r-wasm.org/webr/latest/mounting.html) that bundles several packages.

Ideally, I'd like to be able to bundle this and mount it into a [JupyterLite webr kernel](https://github.com/r-wasm/jupyterlite-webr-kernel) [[related issue](https://github.com/r-wasm/jupyterlite-webr-kernel/issues/7)] to provide a customised, self-contained kernel that bundles all required packages so that packages do not lead to be downloaded from a remote third party url when they are first imported.

