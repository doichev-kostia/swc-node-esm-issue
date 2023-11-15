# Node v20.6 changes to the loaders API

After the node.js v 20.6 [release](https://nodejs.org/en/blog/release/v20.6.0) the `--loader @swc-node/register/esm` option is no longer supported.
The requirement is to use `--import` and register the loader

In this repo there is a simple workaround to use the `@swc-node/register/esm` loader with node v20.6

The part of the register code is taken from the [tsx](https://github.com/privatenumber/tsx/blob/develop/src/esm/index.ts) repo

