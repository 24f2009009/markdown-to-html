# Markdown to HTML Live Preview with Syntax Highlighting

A production-ready single-page HTML app that converts Markdown to HTML in real time with syntax highlighting for code blocks. All content is embedded in the HTML; no external fetch calls.

## Features
- Real-time rendering
- Syntax highlighting for code blocks using highlight.js
- Self-contained: all content is embedded in index.html

## How it works
- On page load, a default Markdown sample is rendered to the output pane.
- As you type in the left pane, the right pane updates automatically.
- Marked parses Markdown and highlight.js applies syntax highlighting to code blocks.

## How to run
- Open index.html in a modern browser (no server required).

## Dependencies
- marked (markdown parser) loaded from CDN
- highlight.js (code highlighting) loaded from CDN
- highlight.js default style loaded from CDN

## Customization
- Edit the DEFAULT_MARKDOWN string inside the script tag in index.html to change the starter content.
