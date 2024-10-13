# zig-npm

This downloads release builds of Zig and publishes them to npm. Trying to make it easier to contribute to Bun and other Zig projects.

## Installation

```sh
npm install @ryoppippi/zig
```

## For Developer

It downloads release builds from https://ziglang.org/download/ and the list of releases from https://github.com/mitchellh/zig-overlay.

Generate:

```sh
bun generate.ts --dry-run
```

## Acknoledgements

This is a frok of [npm-zig](https://github.com/oven-sh/zig-npm)

