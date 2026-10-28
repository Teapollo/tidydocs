# TidyDocs

> **A fast, 100% free, client-side formatting & cleanup engine for Google Docs.**

---

## Overview

**TidyDocs** was built on Google's modern **V8 engine** to replace abandoned tools with a single fast utility sidebar.

- **100% Client-Side**: Executes entirely within your browser's Google Docs session.
- **Text Format Preserving**: Uses a contiguous attribute-slice engine so bold words, italics, and clickable links are never erased during sorting or text cleaning.

---

## Key Features

### 1. Smart Clean Document
- **PDF Line-Wrap Merger**: Intelligently rejoins broken mid-sentence lines from copied multi-column PDF excerpts without gluing headings, lists, or reference citations together.
- **AI Markdown Converter**: Converts ChatGPT, Claude, and Gemini markdown artifacts (`**bold**`, `*italics*`, `### Headings`, and `inline_code` pills) into real Google Docs styles.
- **Non-Destructive Case Sanitizer**: Normalizes lowercase sentence beginnings, fixes Shift-slips (`THe` -> `the`), and capitalizes `I` contractions while strictly protecting properly capitalized proper nouns (`United States`, `Google`, `HuggingFace`, etc.).
- **Spacing Sanitizer**: Strips hidden Unicode zero-width characters (`​`, `﻿`) and collapses redundant duplicate whitespace.

### 2. Paragraph & Outline Sorter
- **Alphabetical (A to Z and Z to A)**: In-place sorting of highlighted paragraphs, table cell contents, and numbered outlines.
- **Academic Surname Sort**: Alphabetizes bibliography and reference lists by author last name while preserving italics and hyperlinks.
- **Natural Numeric Ordering**: Accurately sorts numbered items.
- **Hierarchical Nested Lists**: Reorders parent list items while keeping nested child sub-bullets anchored to their respective parents.

### 3. Numbered Section Organizer
- Automatically detects out-of-order multi-paragraph sections (e.g. `2.3`, `2.1`, `2.2`) and reorganizes them along with their child paragraphs into sequential order (`2.1` -> `2.2` -> `2.3`).
- Keeps terminal sections (`References`, `Appendices`, `Acknowledgments`) anchored in place.

---

## Permissions & OAuth Scopes

TidyDocs requests only the absolute minimum permissions required to operate on the active document:

| Scope | Purpose |
| :--- | :--- |
| `https://www.googleapis.com/auth/documents.currentonly` | Allows TidyDocs to read and format the document where the add-on was launched. |
| `https://www.googleapis.com/auth/script.container.ui` | Allows TidyDocs to render its sidebar panel inside the Google Docs editor window. |

*TidyDocs does **not** request access to your Google Drive, your other files, your email, or your identity.*

---

## Privacy Policy & Terms

- [Privacy Policy](PRIVACY.md)
- [Terms of Service](TERMS.md)

---

## Support & Feedback

If you encounter any issues, have feature suggestions, or want to contribute feedback:
- **Issue Tracker**: [GitHub Issues](https://github.com/alannguyen1306/tidydocs/issues)
- **Ko-fi Support**: [Support me on Ko-fi](https://ko-fi.com/S0M829K7TK)

---

## Author

**Alan Nguyen**

