# fox

[中文版本](./README.cn.md)

A local LLM server built for concurrent work. Drop-in replacement for Ollama and/or OpenAI and Ollama APIs on one port. Requests that share a prompt reuse each other's KV cache instead of each prefilling it. Rust, wrapping llama.cpp.

![fox](https://repo.x-cmd.io/fox.svg)

## Install

```sh
x install fox
```

## Source

- **Upstream**: <https://github.com/ferrumox/fox>
- **Homepage**: <https://ferrumox.com>
- **License**: NOASSERTION

## Release

- **Latest**: `v0.22.1` (2026-08-22)
- **Last commit**: 2026-08-22
- **Assets in release**: 6
- **Published**: 2026-08-22T08:45:47Z

## Popularity

- **Stars**: 187 · **Forks**: 29 · **Open issues**: 5 · **Contributors**: 2

## Totals (cumulative)

- **Releases**: 16 · **Merged PRs**: 0 · **Open PRs**: 1 · **Closed issues**: 1 · **Open issues**: 4 · **Commits**: 428

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 2 | 0 | 1 | 0 | 0 | 30 |
| 90d | 2026-06-12 | 10 | 0 | 1 | 1 | 2 | 281 |
| 360d | 2025-09-15 | 16 | 0 | 1 | 1 | 4 | 396 |

## Code size

Total: **32,004** lines of code across **129** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Rust | 26,168 | 2,779 | 3,025 | 95 |
| Sh | 2,540 | 809 | 348 | 20 |
| Python | 1,846 | 219 | 228 | 11 |
| Json | 675 | 0 | 0 | 2 |
| Makefile | 175 | 57 | 26 | 1 |

## Improve this data

Install metadata for fox lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `fox` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/edit/main/fox.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T04:53:47Z._
