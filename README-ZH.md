# Starcat Pro

<p align="center">
  <img src="./20260706180230_GyAMtI7f.png" alt="Starcat Pro 横幅图" width="100%">
</p>

<p align="center">
  <strong>把 GitHub Stars 变成可搜索的 AI 知识库。</strong>
  <br>
  一款原生 macOS 应用，帮助你整理、理解、找回和评估收藏过的仓库。
</p>

<p align="center">
  <a href="https://starcat.ink"><img alt="落地页" src="https://img.shields.io/badge/落地页-starcat.ink-38BDF8?style=for-the-badge"></a>
  <a href="https://starcat.ink/downloads/Starcat-1.1.0-arm64.dmg"><img alt="下载" src="https://img.shields.io/badge/下载-macOS%20Direct-22C55E?style=for-the-badge"></a>
  <a href="./CHANGELOG-ZH.md"><img alt="更新日志" src="https://img.shields.io/badge/更新日志-release%20notes-FBBF24?style=for-the-badge"></a>
</p>

<p align="center">
  <img alt="macOS 15+" src="https://img.shields.io/badge/macOS-15%2B-0A84FF?style=flat-square&logo=apple">
  <img alt="Apple Silicon" src="https://img.shields.io/badge/Apple%20Silicon-Direct%20Build-111827?style=flat-square&logo=apple">
  <img alt="Native SwiftUI" src="https://img.shields.io/badge/Native-SwiftUI-FA7343?style=flat-square&logo=swift">
  <img alt="Local First" src="https://img.shields.io/badge/Local--First-SQLite-4ADE80?style=flat-square">
  <img alt="BYOK AI" src="https://img.shields.io/badge/BYOK-AI-A78BFA?style=flat-square">
</p>

<p align="center">
  <a href="https://starcat.ink">官网</a>
  ·
  <a href="https://starcat.ink/downloads/Starcat-1.1.0-arm64.dmg">下载</a>
  ·
  <a href="./CHANGELOG-ZH.md">更新日志</a>
  ·
  <a href="https://github.com/dong4j/starcat-pro/issues">反馈问题</a>
  ·
  <a href="./README.md">English</a>
</p>

## 为什么需要 Starcat

GitHub Stars 很容易越攒越多，但真正要重新找回、理解和复用时却很难。Starcat 把扁平收藏夹变成专注的桌面知识库：

- **整理**：用标签、私有笔记、阅读状态和批量操作管理仓库。
- **理解**：阅读 README、生成 AI 摘要、翻译 README，并围绕仓库上下文提问。
- **找回**：用本地全文搜索、筛选、语义搜索和推荐重新发现收藏过的项目。
- **跟踪**：订阅 Release，查看活动和健康度信号，把重要更新留在视线内。

## 核心亮点

| 领域 | Starcat 能做什么 |
| --- | --- |
| 搜索 | 基于 FTS5 的本地全文搜索，覆盖仓库名、描述、topics 和笔记。 |
| AI | 结构化摘要、README 翻译、上下文问答，以及 BYOK Provider 配置。 |
| 整理 | 标签、私有笔记、状态、语言筛选、批量打标和 JSON 导入导出。 |
| Release 工作流 | 订阅关注的仓库，查看新版本，并让重要更新保持可见。 |
| macOS 体验 | 原生 macOS 15+ 应用，三栏布局、菜单栏工作流和专注阅读体验。 |

## 当前可用状态

Starcat 目前以 macOS Direct 版本提供下载，面向 Apple Silicon Mac。核心整理能力免费，Pro 工作流仍在准备中。

- 仅支持 macOS 15+。
- Direct 下载，支持应用内更新。
- Local-first 数据模型：仓库缓存可重建，标签、笔记和状态保存在本地 SQLite。
- BYOK AI：使用你自己的模型 Provider 或 API Key。

## 这个仓库用来做什么

这个仓库是 Starcat Pro 的公开支持与发布说明入口：

- 通过 GitHub Issues 收集 bug、体验问题和功能建议。
- 维护 Starcat 唯一可信的公开更新日志。
- 把公开支持材料和私有应用 / 后端源码分离。

## 这个仓库不包含什么

- 不包含应用源码。
- 不包含后端源码。
- 不包含构建脚本或私有配置。

## 反馈问题

如果要反馈 bug、体验问题或功能建议，请创建 GitHub Issue。

反馈 bug 时，建议附上：

- Starcat 版本。
- macOS 版本和设备类型。
- 复现步骤。
- 预期结果和实际结果。
- 可用时附上截图、录屏或可见错误信息。
