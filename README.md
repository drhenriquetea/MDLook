<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="mdlook-logo-light.svg" />
    <img src="mdlook-logo-svg.svg" alt="MDLook" width="400" />
  </picture>
</p>

<p align="center"><strong>A portable, offline Markdown editor for Windows.</strong><br>Unzip. Run. No install, no Electron.</p>

<p align="center">
  <a href="https://github.com/drhenriquetea/MDLook/releases/latest"><img src="badges/download-button.svg" alt="Download MDLook" /></a>
</p>

<p align="center">
  <a href="#why-mdlook">Why MDLook?</a> &middot;
  <a href="#screenshots">Screenshots</a> &middot;
  <a href="#features">Features</a> &middot;
  <a href="#comparison">Comparison</a> &middot;
  <a href="#faq">FAQ</a> &middot;
  <a href="https://github.com/drhenriquetea/MDLook/issues">Issues</a>
</p>

![Read mode](screenshots/screenshot-read-1.png)

## Why MDLook?

Most Markdown editors are either bloated (Electron), need internet for fonts and math, or force you into a vault/project system just to open a file. MDLook is none of those.

- **Double-click and read.** Register `.md` files once, then double-click any Markdown file and it opens beautifully rendered. No project setup, no vault, no config folders.
- **Live preview as you type.** Split-pane editor with real-time rendering. What you write on the left appears formatted on the right, instantly.
- **Math and diagrams built-in.** KaTeX for LaTeX equations, Mermaid for flowcharts and diagrams. No plugins, no config. Just works.
- **Zero install, works offline.** Unzip a folder, run `MDLook.exe`. Fonts, math, diagrams and syntax highlighting are all embedded, so every feature works with no connection. The one exception is the update notice: once a day it asks GitHub whether a newer release exists. Nothing is downloaded, and a switch in the Help panel turns it off.
- **42 MB total.** Not 300 MB of Chromium. Uses native Windows WebView2.
- **Dark mode and Zen mode.** Full dark theme. Zen mode strips the UI for distraction-free writing.
- **Outline sidebar.** Hierarchical table of contents for navigating long documents. Click any heading to jump, collapse or expand all sections at once.
- **Teleprompter.** Auto-scroll your document at adjustable speed. No other Markdown editor has this.
- **A window per document.** Open three files, get three windows, each remembering its own size and position. Open one that is already open and MDLook brings you to it instead of a duplicate.
- **Keeps up with your files.** Edit a document in another app and MDLook reloads it. If you had unsaved changes, it asks first. `Ctrl+S` saves straight to disk.

## Screenshots

<table>
<tr>
<td><a href="screenshots/screenshot-edit-1.png"><img src="screenshots/screenshot-edit-1.png" width="100%" alt="Edit mode" /></a><br /><strong>Edit mode</strong> — split-pane with live preview</td>
<td><a href="screenshots/screenshot-read-2.png"><img src="screenshots/screenshot-read-2.png" width="100%" alt="Math and diagrams" /></a><br /><strong>Math & Diagrams</strong> — KaTeX + Mermaid, built-in</td>
</tr>
<tr>
<td><a href="screenshots/screenshot-edit-2.png"><img src="screenshots/screenshot-edit-2.png" width="100%" alt="Math and diagrams, edit mode" /></a><br /><strong>Math in Edit mode</strong> — source on the left, render on the right</td>
<td><a href="screenshots/screenshot-color-tokens.png"><img src="screenshots/screenshot-color-tokens.png" width="100%" alt="Color tokens" /></a><br /><strong>Color tokens</strong> — adaptive colored text with swatches</td>
</tr>
<tr>
<td><a href="screenshots/screenshot-read-3.png"><img src="screenshots/screenshot-read-3.png" width="100%" alt="Tables and lists" /></a><br /><strong>Tables & Checklists</strong> — with blockquotes</td>
<td><a href="screenshots/screenshot-collapse.png"><img src="screenshots/screenshot-collapse.png" width="100%" alt="Collapsible sections" /></a><br /><strong>Collapsible sections</strong> — fold any heading, block counts</td>
</tr>
<tr>
<td><a href="screenshots/screenshot-dark-night-mode.png"><img src="screenshots/screenshot-dark-night-mode.png" width="100%" alt="Dark mode" /></a><br /><strong>Dark mode</strong> — full theme, easy on the eyes</td>
<td><a href="screenshots/screenshot-dark-wide.png"><img src="screenshots/screenshot-dark-wide.png" width="100%" alt="Dark wide layout" /></a><br /><strong>Wide layout</strong> — dark mode + syntax highlighting</td>
</tr>
<tr>
<td><a href="screenshots/screenshot-zen-mode.png"><img src="screenshots/screenshot-zen-mode.png" width="100%" alt="Zen mode" /></a><br /><strong>Zen mode</strong> — distraction-free writing</td>
<td><a href="screenshots/screenshot-source-1.png"><img src="screenshots/screenshot-source-1.png" width="100%" alt="Source view" /></a><br /><strong>Source view</strong> — raw Markdown, monospace</td>
</tr>
<tr>
<td><a href="screenshots/screenshot-outline-light.png"><img src="screenshots/screenshot-outline-light.png" width="100%" alt="Outline sidebar" /></a><br /><strong>Outline sidebar</strong> — hierarchical TOC for navigation</td>
<td><a href="screenshots/screenshot-outline-dark.png"><img src="screenshots/screenshot-outline-dark.png" width="100%" alt="Outline sidebar dark" /></a><br /><strong>Outline (dark)</strong> — click any heading to jump</td>
</tr>
<tr>
<td><a href="screenshots/screenshot-help-modal.png"><img src="screenshots/screenshot-help-modal.png" width="100%" alt="Help modal" /></a><br /><strong>Help & shortcuts</strong> — built-in reference</td>
<td><img src="screenshots/demo-teleprompter.gif" width="100%" alt="Teleprompter demo" /><br /><strong>Teleprompter</strong> — auto-scroll at adjustable speed</td>
</tr>
</table>

## Features

- ✏️ **Live split-pane editor** with formatting toolbar
- 🧮 **LaTeX math** via KaTeX (inline `$E=mc^2$` and display `$$blocks$$`)
- 📊 **Mermaid diagrams** (flowcharts, sequence diagrams, Gantt charts)
- 🎨 **Syntax highlighting** for 30+ languages
- 🌙 **Dark/light theme** toggle
- 🧘 **Zen mode** for distraction-free writing
- 📐 **Wide/narrow layout** toggle
- 🧭 **Outline sidebar** (hierarchical TOC for navigating long documents)
- 📂 **Collapsible sections** (click any heading to fold)
- 🎬 **Teleprompter mode** (auto-scroll for presentations)
- 📤 **Export** to standalone HTML
- 🔗 **File association** (register `.md` files with a custom document icon)
- 🪟 **A window per document** (size, position and maximized state remembered per file)
- 🕒 **Recent files** (menu beside Open, start page, and the Windows jump list)
- 🔄 **Reloads files changed on disk** (with a prompt when you have unsaved edits)
- ☑️ **Clickable task checkboxes** in the preview
- 🖍️ **Highlight colours** (`=={green}text==`, eight named colours or any hex)
- 🖨️ **Print / export to PDF** (`Ctrl+P`)
- 💾 **Direct save to disk** (`Ctrl+S`, no download dialogs)
- 🔎 **Find** (Ctrl+F) with match navigation
- 🔤 **Serif or sans-serif** for the document text (Help panel)
- 🎨 **Color tokens** for adaptive colored text

See [GUIDE.md](GUIDE.md) for the full feature reference with examples.

## Comparison

| | MDLook | Typora | Obsidian | VS Code |
|---|---|---|---|---|
| Portable (no install) | **Yes** | No | No | No |
| Works offline | **Yes**, except an optional daily update check | Partial | Partial | No |
| Double-click to open `.md` | **Yes** | Yes | No | No |
| Math (KaTeX) | **Built-in** | Built-in | Plugin | Plugin |
| Diagrams (Mermaid) | **Built-in** | Built-in | Plugin | Plugin |
| Teleprompter mode | **Yes** | No | No | No |
| Size | **42 MB** | ~80 MB | ~300 MB | ~500 MB |
| Free | **Yes** | $15 | Free* | Free |
| Electron | **No** | Yes | Yes | Yes |

*\*Obsidian Sync and Publish are paid.*

## Download

**[Portable zip](https://github.com/drhenriquetea/MDLook/releases/latest)** (34 MB) - Unzip anywhere, run `MDLook.exe`. Works from a USB stick, and keeps its settings beside the executable.

**[Installer](https://github.com/drhenriquetea/MDLook/releases/latest)** (23 MB) - Standard Next > Next > Finish setup.

## FAQ

**Will MDLook support macOS or Linux?**

It's on the radar. MDLook started as a personal tool I built to solve my own problem as a physician. Windows is what I use daily, so that's where it runs today. If there's enough demand, cross-platform is the natural next step. [Open an issue](https://github.com/drhenriquetea/MDLook/issues) if this matters to you; that's how I gauge interest.

**Is MDLook free?**

MDLook is currently free to use.

**My antivirus flagged MDLook as suspicious.**

Most likely a false positive. MDLook is built with PyInstaller, which bundles a Python runtime into a single executable, and many antivirus engines flag PyInstaller apps on that basis alone. Every release lists the SHA-256 of both downloads so you can confirm the file you have is the file that was published, and you are welcome to submit it to VirusTotal yourself.

**How do I report a bug or request a feature?**

[Open an issue](https://github.com/drhenriquetea/MDLook/issues) on this repository.

## License

Copyright 2026 Henrique Djosci Coêlho de Sá. All rights reserved.
