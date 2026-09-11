# fox

[English version](./README.md)

A local LLM server built for concurrent work. Drop-in replacement for Ollama and/or OpenAI and Ollama APIs on one port. Requests that share a prompt reuse each other's KV cache instead of each prefilling it. Rust, wrapping llama.cpp.

![fox](https://repo.x-cmd.io/fox.svg?lang=zh)

## 安装

```sh
x install fox
```

## 代码洞察

合计: **32,004** 行代码（覆盖前 5 种语言、共 **129** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 26,168 | 2,779 | 3,025 | 95 |
| Sh | 2,540 | 809 | 348 | 20 |
| Python | 1,846 | 219 | 228 | 11 |
| Json | 675 | 0 | 0 | 2 |
| Makefile | 175 | 57 | 26 | 1 |

## 源代码

- **上游仓库**: <https://github.com/ferrumox/fox>
- **官网**: <https://ferrumox.com>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v0.22.1` (2026-08-22)
- **最近提交**: 2026-08-22
- **Release 含资产**: 6 个

## 流行度

- **Star**: 187 · **Fork**: 29 · **开放 issue**: 5 · **贡献者**: 2

## 累计统计

- **发布数**: 16 · **已合并 PR**: 0 · **开放 PR**: 1 · **已关闭 issue**: 1 · **开放 issue**: 4 · **提交数**: 428

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 2 | 0 | 1 | 0 | 0 | 30 |
| last60d | 2026-07-13 | 7 | 0 | 1 | 1 | 0 | 211 |
| 90d | 2026-06-13 | 10 | 0 | 1 | 1 | 2 | 281 |
| last180d | 2026-03-15 | 11 | 0 | 1 | 1 | 4 | 320 |
| 360d | 2025-09-16 | 16 | 0 | 1 | 1 | 4 | 396 |
| last720d | 2024-09-21 | 16 | 0 | 1 | 1 | 4 | 428 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz) | 32.4 MiB | `native/linux/x64/glibc` |
| [fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz.sha256](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu-vulkan.tar.gz.sha256) | 116 B | `native/linux/x64/glibc` |
| [fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz) | 20.1 MiB | `native/linux/x64/glibc` |
| [fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz.sha256](https://github.com/ferrumox/fox/releases/download/v0.22.1/fox-0.22.1-x86_64-unknown-linux-gnu.tar.gz.sha256) | 109 B | `native/linux/x64/glibc` |
| [install.ps1](https://github.com/ferrumox/fox/releases/download/v0.22.1/install.ps1) | 3.6 KiB | `other` |
| [install.sh](https://github.com/ferrumox/fox/releases/download/v0.22.1/install.sh) | 6.5 KiB | `other` |

## 改进这些数据

fox 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `fox` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/fox.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T00:12:27Z._
