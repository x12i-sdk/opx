# @x12i/opx-docs usage example

OpX docs knowledge SDK — Memorix acceptance pack layout, source, harness. Install as a devDependency only.

This consuming application demonstrates **list the bundled guides and read a use case** using the published npm package, pinned to `1.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

This is a documentation knowledge SDK. It is installed as a development dependency. The example lists its books and use cases, then reads the first available use-case guide from the package.

## When to use the package

- Install @x12i/opx-docs as a development dependency so the product guides and package index are available to developers and coding assistants.
- Read the bundled opx documentation or use-case catalog without requiring a live documentation website.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/opx-docs)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
