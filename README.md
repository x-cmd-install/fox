# fox

A local LLM server built for concurrent work. Drop-in replacement for Ollama and/or OpenAI and Ollama APIs on one port. Requests that share a prompt reuse each other's KV cache instead of each prefilling it. Rust, wrapping llama.cpp.

- **Upstream**: <https://github.com/ferrumox/fox>
- **Homepage**: <https://ferrumox.com>
- **Latest release**: `v0.22.1` (2026-08-22)
- **Last commit**: 2026-08-22
- **License**: NOASSERTION
- **Stars**: 187 · **Forks**: 29 · **Open issues**: 5 · **Contributors**: 2

## Installation

```sh
x install fox
```

See <https://x-cmd.com/install/fox> for details.

## Data

This mirror is auto-maintained by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action). Latest card snapshot: `data/card/260909.yml`. Merged card+release view: `data/latest.report.yml`.

_Last regenerated: 2026-09-09T18:51:11Z._
