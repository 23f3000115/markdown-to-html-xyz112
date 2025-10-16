# README

## Overview
This web app provides a simple Markdown editor with two tabs that let you switch between the raw Markdown source and the rendered HTML. It includes a live word count that updates as you type.

Key features:
- Tabs (#markdown-tabs) with at least two buttons (Source and HTML).
- Live word count displayed in the element #markdown-word-count.
- Switching tabs toggles visibility between the Markdown source editor and the rendered HTML preview.
- Lightweight, dependency-free Markdown renderer supporting headings, lists, bold/italic, inline/fenced code, and links.

## Setup
No build steps are required.

- Option 1: Open index.html directly in your browser.
- Option 2: Serve with any static server (e.g., npx serve .) for best local file handling.

All CSS and JavaScript are included inline.

## Usage
- Type Markdown in the Source tab.
- Click the HTML tab to view the rendered output.
- The word count at the top right updates automatically as you type.
- The preview updates live even while you type in the Source tab.

Tips:
- Use # through ###### for headings.
- Use - or * for unordered lists.
- Use **bold** and *italic* for emphasis.
- Use backticks for inline code and triple backticks for fenced code blocks.
- Use [text](https://example.com) for links.

## Improvements from Previous Version (Round 2)
- Added a tab bar (#markdown-tabs) with two buttons to switch between Source (Markdown) and HTML (rendered) views.
- Implemented live word counting displayed in #markdown-word-count that updates on every keystroke.
- Ensured that switching tabs correctly toggles visibility between the editable source and the rendered HTML content.