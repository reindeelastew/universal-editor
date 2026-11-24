# Universal Editor 0.2

A lightweight, browser-based prototype for cross-disciplinary document creation. The first focus is scientific notation and practical document export.

## Try it
Open [index.html](./index.html) in a modern browser. No build step, package installation, account or server is required.

## Features
- Rich-text editing: bold, italic, underline, headings, lists, quotes and tables
- Superscript and subscript
- Lightweight chemistry notation conversion (e.g. `H2SO4` → `H₂SO₄`)
- Symbol palette and quick chemistry inputs
- Local autosave, including document title
- Character count
- Import HTML, TXT and Universal Editor JSON backup files
- Export standalone HTML
- Export/import JSON backup (`.uebackup.json`)
- Print / Save as PDF

## Storage and privacy
Documents are saved in the current browser's local storage. They are not uploaded to a server. Use **バックアップ** to download a portable JSON backup. Do not commit personal documents or backup files to this repository.

## GitHub Pages
This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

1. Push the project files to the `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions** as the deployment source.
4. The workflow deploys the repository root after each push to `main`.

## Limitations
- No account, cloud sync or collaboration
- No DOCX import/export yet
- No AI features
- Chemistry conversion is intentionally lightweight, not a complete chemical notation parser
- Uses browser `contenteditable`; complex formatting may vary between browsers
- Imported HTML is sanitized, but still avoid opening files from untrusted sources

## Product direction
Start as a companion tool for existing document editors, then evolve into a standalone cross-platform workspace. Preserve editable structured content and interoperability.
