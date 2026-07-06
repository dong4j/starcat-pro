# Starcat Pro

<p align="center">
  <img src="./20260706180230_GyAMtI7f.webp" alt="Starcat Pro banner" width="100%">
</p>

<p align="center">
  <strong>Turn GitHub Stars into a searchable AI knowledge base.</strong>
  <br>
  A native macOS app for organizing, understanding, rediscovering, and evaluating the repositories you save.
</p>

<p align="center">
  <a href="https://starcat.ink"><img alt="Landing page" src="https://img.shields.io/badge/landing%20page-starcat.ink-38BDF8?style=for-the-badge"></a>
  <a href="https://starcat.ink/downloads/Starcat-1.1.0-arm64.dmg"><img alt="Download" src="https://img.shields.io/badge/download-macOS%20Direct-22C55E?style=for-the-badge"></a>
  <a href="./CHANGELOG.md"><img alt="Changelog" src="https://img.shields.io/badge/changelog-release%20notes-FBBF24?style=for-the-badge"></a>
</p>

<p align="center">
  <img alt="macOS 15+" src="https://img.shields.io/badge/macOS-15%2B-0A84FF?style=flat-square&logo=apple">
  <img alt="Apple Silicon" src="https://img.shields.io/badge/Apple%20Silicon-Direct%20Build-111827?style=flat-square&logo=apple">
  <img alt="Native SwiftUI" src="https://img.shields.io/badge/Native-SwiftUI-FA7343?style=flat-square&logo=swift">
  <img alt="Local First" src="https://img.shields.io/badge/Local--First-SQLite-4ADE80?style=flat-square">
  <img alt="BYOK AI" src="https://img.shields.io/badge/BYOK-AI-A78BFA?style=flat-square">
</p>

<p align="center">
  <a href="https://starcat.ink">Website</a>
  ·
  <a href="https://starcat.ink/downloads/Starcat-1.1.0-arm64.dmg">Download</a>
  ·
  <a href="./CHANGELOG.md">Changelog</a>
  ·
  <a href="https://github.com/dong4j/starcat-pro/issues">Report an issue</a>
  ·
  <a href="./README-ZH.md">中文</a>
</p>

## Why Starcat

GitHub Stars are easy to collect and hard to reuse. Starcat turns a flat star list into a focused desktop knowledge base:

- **Organize** repositories with tags, private notes, reading status, and batch operations.
- **Understand** repositories with rendered READMEs, AI summaries, translation, and repo-level context.
- **Rediscover** saved projects with local full-text search, filters, semantic search, and recommendations.
- **Track** important projects with release subscriptions, activity, and health signals.

## Highlights

| Area | What Starcat Helps With |
| --- | --- |
| Search | FTS5 local full-text search across repo names, descriptions, topics, and notes. |
| AI | Structured summaries, README translation, contextual Q&A, and BYOK provider setup. |
| Organization | Tags, private notes, status, language filters, batch tagging, and JSON import/export. |
| Release workflow | Subscribe to repositories, review new releases, and keep important updates visible. |
| macOS experience | Native macOS 15+ app with a three-column layout, menu bar workflows, and focused reading. |

## Current Availability

Starcat currently ships as a macOS Direct build for Apple Silicon Macs. Core organization features are free while Pro workflows are being prepared.

- macOS 15+ only.
- Direct download with in-app update support.
- Local-first data model: repo cache can be rebuilt; tags, notes, and status stay in local SQLite.
- BYOK AI: configure your own model provider or API key.

## What This Repository Is For

This repository is the public support and release-notes home for Starcat Pro:

- Collect bug reports, usability issues, and feature requests through GitHub Issues.
- Publish Starcat release notes in one canonical changelog.
- Keep public support material separate from private app and backend source trees.

## What This Repository Does Not Contain

- No application source code.
- No backend source code.
- No build scripts or private configuration.

## Feedback

Please open a GitHub Issue for bugs, usability problems, and product suggestions.

For bug reports, include:

- Starcat version.
- macOS version and device type.
- Steps to reproduce.
- Expected result and actual result.
- Screenshot, screen recording, or visible error message when available.
