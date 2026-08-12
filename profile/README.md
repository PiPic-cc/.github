# PiPic

[PiPic Image Compressor](https://pipic.cc/about) compresses PNG, JPEG,
WebP and AVIF in the browser for free and exposes developer workflows through
the official [@pipic/cli](https://www.npmjs.com/package/@pipic/cli) and HTTP
API.

- Web: https://pipic.cc/
- CLI source: https://github.com/PiPic-cc/pipic-cli
- npm: https://www.npmjs.com/package/@pipic/cli
- API and CLI docs: https://pipic.cc/cli

## Web app

Drag, drop, done — [pipic.cc](https://pipic.cc/)

- Batch up to 100 images, 8 MB each
- Smart lossy compression that preserves visual quality
- Images are deleted the moment compression finishes — never stored,
  never used to train AI models ([privacy](https://pipic.cc/privacy))
- Available in five languages

## CLI — built for CI and coding agents

```bash
npx @pipic/cli photos/ --replace
```

- Zero runtime dependencies, single-file executable
- NDJSON output and stable exit codes, designed to be parsed by
  scripts and agents
- Sign in once with `pipic login`, works headless in CI

[Source](https://github.com/PiPic-cc/pipic-cli) ·
[npm](https://www.npmjs.com/package/@pipic/cli) ·
[Docs](https://pipic.cc/cli)
