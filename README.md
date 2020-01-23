# `typedoc-object-repro`

This is a bug repro repo intended to show an issue with typedoc's library mode where members of "namespace objects" are not present in the generated docs.

## Usage

You can check `docs/index.html` without generating it if you're fine using what my machine generated, but if you want to generate it yourself, run:

```
yarn install
yarn build-docs
```
