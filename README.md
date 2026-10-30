# md-to-pdf-word

**Free online converter: Markdown, Word and LaTeX → a typeset PDF and an editable Word document.**
Correct Chinese text, tables with merged cells, numbered equations, references, cover pages and Chinese official documents (GB/T 9704).

👉 **[https://mdpdfword.com](https://mdpdfword.com/)** · [中文](https://mdpdfword.com/zh/) · [Français](https://mdpdfword.com/fr/) · [Deutsch](https://mdpdfword.com/de/) · [日本語](https://mdpdfword.com/ja/) · [Español](https://mdpdfword.com/es/)

This repository holds the public documentation and is where you can **report problems and suggest improvements**. The converter's source code is not published here.

## What it does

| Page | |
|---|---|
| [Markdown to PDF](https://mdpdfword.com/markdown-to-pdf/) | A typeset PDF with embedded fonts — no garbled Chinese, no broken tables |
| [Markdown to Word](https://mdpdfword.com/markdown-to-word/) | An editable .docx with real heading styles, table of contents, captions and editable equations |
| [Restyle a Word file](https://mdpdfword.com/word-template/) | Accept or reject all tracked changes and reformat a .docx consistently |
| [LaTeX to Word](https://mdpdfword.com/latex-to-word/) | Turn a .tex project into Word, with equations, references and figures |
| [Chinese official documents](https://mdpdfword.com/chinese-official-documents/) | Red-header documents laid out to GB/T 9704 |
| [For AI assistants (MCP)](https://mdpdfword.com/mcp/) | Let Claude Code, Codex or Cursor produce PDF and Word files |

- Free, no sign-up. Files are deleted automatically after 2 hours (or immediately on request).
- Limits: 20 MB per file, 60 MB per upload, 30 conversions per hour.
- [Writing syntax](https://mdpdfword.com/syntax/) · [Guides](https://mdpdfword.com/guides/) · [FAQ](https://mdpdfword.com/faq/) · [Privacy](https://mdpdfword.com/privacy/)

## Use it from an AI assistant (MCP, no token)

```bash
# Claude Code
claude mcp add --transport http md-to-pdf-word https://mdpdfword.com/mcp -s user
```

```toml
# Codex: ~/.codex/config.toml
[mcp_servers.md-to-pdf-word]
url = "https://mdpdfword.com/mcp"
tool_timeout_sec = 300
```

Then ask: *“Convert report.md in this folder to PDF and Word.”*

## Feedback

- [Report a problem](../../issues/new?template=problem.yml) · [Suggest an improvement](../../issues/new?template=suggestion.yml)
- Or use **Feedback** on any page of the website.

---

## 中文简介

免费在线把 Markdown、Word、LaTeX 转成排版精美的 PDF 和可编辑的 Word：中文不乱码，支持合并单元格、公式编号、参考文献、封面和党政机关公文（GB/T 9704）。免注册，文件 2 小时后自动删除。

- 网站：[https://mdpdfword.com/zh/](https://mdpdfword.com/zh/)
- 给 AI 助手用（MCP，无需令牌）：[https://mdpdfword.com/zh/mcp/](https://mdpdfword.com/zh/mcp/)
- 反馈问题或建议：在本仓库 [提 issue](../../issues/new/choose)，或点击网站任意页面的“反馈”。
