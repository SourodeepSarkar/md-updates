# md v1
![Platform](https://img.shields.io/badge/platform-macOS%2026%2B-black?style=for-the-badge&logo=apple)
![SwiftUI](https://img.shields.io/badge/Built%20With-SwiftUI-orange?style=for-the-badge&logo=swift)

<table>
<tr>

<td width="260" align="center">

<img width="220" height="220" alt="md Icon" src="https://github.com/user-attachments/assets/32ac5c89-8dca-4b72-b944-6c5825fd22a9" />

</td>

<td valign="middle">

A beautiful, native Markdown reader for macOS built entirely with SwiftUI.

md is designed as a distraction-free, read-only Markdown experience that feels at home on macOS Tahoe. It focuses on typography, structure, and fast navigation while intentionally leaving editing to your preferred Markdown editor.

Built with Apple's latest SwiftUI APIs and optimized for modern macOS workflows.

<br>

**Core Focus**
- Beautiful Markdown Rendering
- Read-Only by Design
- Document Outline Navigation
- Native macOS Experience
- Privacy-First
- Lightning Fast Performance

</td>

</tr>
</table>

---

# Highlights

## Beautiful Markdown Rendering

- Clean typography optimized for reading
- Automatic heading hierarchy
- Lists, quotes, code blocks and tables
- Adaptive spacing for long-form documents
- Text selection throughout the document

## Native macOS Experience

- Built entirely with SwiftUI
- Apple-inspired Liquid Glass interface
- Native toolbar and window behaviors
- Smooth scrolling
- Responsive layout
- Optimized for macOS Tahoe

## Document Outline

- Automatically generated sidebar
- Heading-based navigation
- Jump instantly to any section
- Keeps large documents easy to browse

## Reading Controls

- Adjustable zoom level
- One-click zoom reset
- Copy Markdown source
- Reveal original file in Finder
- Keyboard-friendly interface

## Obsidian Integration

- Open the current file directly in Obsidian
- Automatically detects if Obsidian is installed
- Download shortcut when unavailable
- Read in md, edit in your preferred editor

## Read-Only Workflow

md intentionally never edits your files.

There are:
- No accidental saves
- No autosave
- No modified document indicators
- No save dialogs

Your Markdown files remain untouched.

---

# Technical Stack

- SwiftUI
- AppKit Interoperability
- FileDocument
- Native Markdown Parser
- Apple Liquid Glass APIs
- NavigationSplitView

---

# Privacy

md is completely local.

- No telemetry
- No analytics
- No cloud services
- No background syncing
- No internet connection required

All files remain on your Mac.

---

# Requirements

- macOS Tahoe (macOS 26) or later

---

# Features

- Read Markdown files instantly
- Automatic outline generation
- Syntax-aware rendering
- Adjustable reading zoom
- Copy Markdown source
- Reveal file in Finder
- Open directly in Obsidian
- Native SwiftUI interface
- Read-only document viewer

---

# Known Limitations

md is intentionally **not** a Markdown editor.

For editing, use your preferred editor such as Obsidian, then reopen the document in md for distraction-free reading.

Because md may be distributed without Apple Developer notarization:

- macOS Gatekeeper warnings may appear
- First launch may require:
  - Right Click → Open

This does not affect functionality.

---

# Installation

1. Download **md.zip**
2. Extract the archive
3. Move **md.app** into Applications
4. Launch md
5. Open any Markdown (`.md`) document

---

# Roadmap

Planned features include:

- Image rendering
- Mermaid diagram support
- Math (LaTeX) rendering
- Internal Markdown links
- Table of Contents improvements
- Better code syntax highlighting
- Reading themes
- Reader mode customization
- Performance optimizations
- Quick Look integration

---

# Philosophy

md is built around one simple idea:

> Read beautifully. Edit elsewhere.

Rather than trying to become another full-featured Markdown editor, md focuses exclusively on creating an elegant, native reading experience that feels like Preview for Markdown.

---

# Feedback

Bug reports, feature requests, and suggestions are welcome through GitHub Issues.

Thank you for using md.
