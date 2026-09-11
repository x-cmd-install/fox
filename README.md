# fox

[中文版本](./README.cn.md)

A local LLM server built for concurrent work. Drop-in replacement for Ollama and/or OpenAI and Ollama APIs on one port. Requests that share a prompt reuse each other's KV cache instead of each prefilling it. Rust, wrapping llama.cpp.

![fox](https://repo.x-cmd.io/fox.svg)

## Install

```sh
x install fox
```

## Code insight

Total: **32,004** lines of code across **129** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Rust | 26,168 | 2,779 | 3,025 | 95 |
| Sh | 2,540 | 809 | 348 | 20 |
| Python | 1,846 | 219 | 228 | 11 |
| Json | 675 | 0 | 0 | 2 |
| Makefile | 175 | 57 | 26 | 1 |

## Source

- **Upstream**: <https://github.com/ferrumox/fox>
- **Homepage**: <https://ferrumox.com>
- **License**: NOASSERTION

## Release

- **Latest**: `v0.22.1` (2026-08-22)
- **Last commit**: 2026-08-22
- **Assets in release**: 6

## Popularity

- **Stars**: 187 · **Forks**: 29 · **Open issues**: 5 · **Contributors**: 2

## Totals (cumulative)

- **Releases**: 16 · **Merged PRs**: 0 · **Open PRs**: 1 · **Closed issues**: 1 · **Open issues**: 4 · **Commits**: 428

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 2 | 0 | 1 | 0 | 0 | 30 |
| last60d | 2026-07-13 | 7 | 0 | 1 | 1 | 0 | 211 |
| 90d | 2026-06-13 | 10 | 0 | 1 | 1 | 2 | 281 |
| last180d | 2026-03-15 | 11 | 0 | 1 | 1 | 4 | 320 |
| 360d | 2025-09-16 | 16 | 0 | 1 | 1 | 4 | 396 |
| last720d | 2024-09-21 | 16 | 0 | 1 | 1 | 4 | 428 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz) | 32.4 MiB | `native/linux/x64/glibc` |
| [fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz.sha256](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz.sha256) | 116 B | `native/linux/x64/glibc` |
| [fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz) | 20.1 MiB | `native/linux/x64/glibc` |
| [fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz.sha256](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz.sha256) | 109 B | `native/linux/x64/glibc` |
| [install.ps1](https://github.com/ferrumox/fox/releases/download/v0.22.1/install.ps1) | 3.6 KiB | `other` |
| [install.sh](https://github.com/ferrumox/fox/releases/download/v0.22.1/install.sh) | 6.5 KiB | `other` |

## Improve this data

Install metadata for fox lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `fox` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/fox.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T00:12:26Z._
