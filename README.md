# Markdown Editor

A Markdown editor that lives in a single HTML file. Open `index.html` in a browser and start writing. There is no build step, no server, and no network access required.

## Features

- **Live preview** with GitHub-flavored Markdown: tables, task lists, strikethrough, fenced code blocks.
- **Three views**: Edit, Split, and Preview. In Split view the two panes scroll together.
- **Syntax highlighting** in code blocks.
- **Table of contents** sidebar that tracks the section you are reading and jumps to a heading on click.
- **Toolbar and shortcuts** for bold, italic, strikethrough, inline code, links, images, headings, lists, task lists, blockquotes, tables, and horizontal rules.
- **Smart editing**: lists continue on Enter, Tab and Shift+Tab indent and outdent, and empty list items end the list.
- **Dark and light themes**, following the system setting by default.
- **Autosave** to browser storage, so an unsaved draft survives a reload.
- **Open, save, and export**. Open a `.md` file with the folder button or by dragging it onto the window. In Chrome and Edge, Save writes straight back to the opened file; other browsers download a copy. Export produces a standalone, styled HTML page.

## Keyboard shortcuts

| Action | Shortcut |
| --- | --- |
| Bold | ⌘B |
| Italic | ⌘I |
| Inline code | ⌘E |
| Link | ⌘K |
| Save | ⌘S |
| Edit / Split / Preview | ⌘1 / ⌘2 / ⌘3 |
| Toggle table of contents | ⌘. |
| Indent / outdent | Tab / Shift+Tab |

On Windows and Linux, use Ctrl in place of ⌘.

## Usage

Download `index.html` and open it in any modern browser. Everything the editor needs is bundled inside the file, so it also works offline and from a USB stick.

Writing back to an opened file uses the File System Access API, which is currently available in Chromium-based browsers. Elsewhere, Save downloads the file instead.

## Built with

The file bundles three open-source libraries:

- [marked](https://github.com/markedjs/marked) for Markdown parsing (MIT)
- [DOMPurify](https://github.com/cure53/DOMPurify) for HTML sanitizing (Apache 2.0 / MPL 2.0)
- [highlight.js](https://github.com/highlightjs/highlight.js) for code highlighting (BSD-3-Clause)

## License

MIT. See [LICENSE](LICENSE).
