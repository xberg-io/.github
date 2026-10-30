<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/xberg-io/assets@v1/banner/readme-banner-dark.svg">
    <img alt="Xberg" width="420" src="https://cdn.jsdelivr.net/gh/xberg-io/assets@v1/banner/readme-banner-light.svg">
  </picture>
</p>

<p align="center"><strong>Open-source content intelligence with a Rust core and native bindings for every major language.</strong></p>

<p align="center">
  <a href="https://docs.xberg.io"><img src="https://img.shields.io/badge/Docs-xberg.io-007ec6" alt="Documentation"></a>
  <a href="https://discord.gg/xt9WY3GnKR"><img src="https://img.shields.io/badge/Discord-Join-007ec6?logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://github.com/xberg-io/xberg/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-007ec6" alt="License"></a>
</p>

## Ecosystem

- [xberg](https://github.com/xberg-io/xberg) — the open-source content-intelligence engine: text, tables, and metadata from 100+ formats, with OCR, transcription, and code intelligence.
- [crawlberg](https://github.com/xberg-io/crawlberg) — web crawling and scraping with HTML→Markdown and headless-Chrome fallback.
- [html-to-markdown](https://github.com/xberg-io/html-to-markdown) — fast, lossless HTML→Markdown engine.
- [liter-llm](https://github.com/xberg-io/liter-llm) — universal LLM API client with native bindings and a catalog of 170+ providers.
- [tree-sitter-language-pack](https://github.com/xberg-io/tree-sitter-language-pack) — tree-sitter grammars for 300+ languages and code-intelligence primitives.
- [sceptre](https://github.com/xberg-io/sceptre) — EasyOCR's accuracy in a single Rust binary: CRAFT text detection and gen2 CRNN recognition over ONNX, with no Python runtime.
- [alef](https://github.com/xberg-io/alef) — the polyglot binding generator that produces every per-language binding across the polyglot repos.
- [sdks](https://github.com/xberg-io/sdks) — official client SDKs for the extraction API served by Xberg Enterprise and Xberg Pro.

## Why Xberg

- **Polyglot** — xberg, crawlberg, html-to-markdown, liter-llm, and tree-sitter-language-pack each have one Rust core, and alef generates their bindings for every major language, so each binding shares one API over the same core.
- **Runs anywhere** — use xberg as a library, CLI, REST API, MCP server, or Docker image; it runs on CPU by default, with no GPU required.
- **Built for RAG** — xberg ships chunking, local or provider-hosted embeddings, and reranking; tree-sitter-language-pack splits code into syntax-aware chunks.
- **MIT licensed** — every repository above is MIT; bundled third-party components keep their own licenses (see each repo's ATTRIBUTIONS.md where present; xberg also ships THIRD_PARTY_LICENSES.md).

## Community

- Discord: <https://discord.gg/xt9WY3GnKR>
- LinkedIn: <https://www.linkedin.com/company/xberg-io>
- Contact: <contact@xberg.io>

Built with care in Kreuzberg, Berlin.
