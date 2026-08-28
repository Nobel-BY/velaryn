# Velaryn

**Knowledge, in motion.**

Velaryn is a local-first AI knowledge base and agent workspace designed for Android tablets. It combines original-layout PDF/DOCX reading, local hybrid retrieval, traceable citations, Markdown knowledge links, evidence-aware agents, controlled knowledge writes, and an MCP knowledge bridge.

- Website: https://velaryn.cn/
- Download: https://velaryn.cn/download/
- Documentation: https://velaryn.cn/docs/
- Current release: v0.9.5 Beta, Android 12+, ARM64

Version 0.9.5 completes the web clipping and active reading workflow. Shared web pages are extracted in an isolated WebView, cleaned, previewed, deduplicated, and stored as Markdown with a script-free HTML snapshot. PDF, DOCX, Markdown, and text readers now provide excerpt, explain, translate, ask, note, link, and flashcard actions. Derived notes preserve exact source anchors and can jump back to the original material. Version 0.9.4 introduced Android system sharing and the persistent capture inbox that this release builds on.

Version 0.9.3 adds reproducible retrieval evaluation, query rewriting, bounded multi-query recall, parent-context expansion, optional model reranking, and unified versioned Markdown writes for Agent and MCP. Single and batch changes show line diffs, reject stale versions, preserve audit records, and can restore history as a new version.

Version 0.9.2 focuses on Creation Spaces: independent tablet-first project containers with file trees, ZIP import/export, lightweight editing, isolated web preview, DOM element picking, reviewable multi-file patches, and automatic checkpoints. It also adds evidence-aware research workflows and explicit knowledge-source scoping. See [CHANGELOG.md](CHANGELOG.md) for details.

This repository is the public product home and issue tracker; it is not a claim that the complete application source is published here. Velaryn is customized from Mintplex Labs' AnythingLLM Mobile under the MIT License. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
