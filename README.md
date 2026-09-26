# Mudassar Hussain Hashmi — Author Site

A static publicity site for four publisher-style Python field references, plus the author's academic research profile.

**Live pages**
- `index.html` — home: hero, key stats, book previews
- `books.html` — full details for all four books
- `research.html` — author bio and Google Scholar record

## Structure

```
.
├── index.html
├── books.html
├── research.html
├── assets/
│   ├── css/
│   │   └── main.css
│   └── img/
│       ├── book1.jpg   # The Python Reference
│       ├── book2.jpg   # The Matplotlib Reference
│       ├── book3.jpg   # The PySide6 Reference (Vol. I)
│       └── book4.jpg   # The PySide6 Reference — Engineering Projects (Vol. II)
├── LICENSE
├── .gitignore
└── README.md
```

## Running locally

No build step or dependencies. Either open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, open **Pages**.
3. Under **Source**, select the `main` branch and the `/ (root)` folder.
4. Save. The site will publish at `https://<username>.github.io/<repo-name>/`.

## Editing content

- Text and stats live directly in the HTML files — edit `index.html`, `books.html`, or `research.html` and refresh.
- Shared styling (colors, type, layout) lives in `assets/css/main.css`.
- Book cover images are in `assets/img/`; replace them with the same filenames to update covers without touching the HTML.

## License

Site code is available under the MIT License (see `LICENSE`). Book cover artwork and book/author content are © Mudassar Hussain Hashmi — all rights reserved.
