# Python for Engineers and Scientists (#python4tech)

A static publicity site for four publisher-style Python field references, plus the author's academic research profile — restructured as a home page that gates into three sections: **Books**, **Publications**, and **Personal Profile**.

```
Home
 |----- Books
 |----- Publications
 |----- Personal Profile
```

**Live pages**
- `index.html` — home: brand, hero, key stats, and the three gateway cards (Books / Publications / Personal Profile)
- `books.html` — full details for all four books
- `publications.html` — full publication list with readable abstracts and DOI links, ScienceDirect-style
- `profile.html` — personal profile: bio, education, research & industry experience, honors, grants, skills, certifications, and Google Scholar summary

## Structure

```
.
├── index.html
├── books.html
├── publications.html
├── profile.html
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

- Text and stats live directly in the HTML files — edit `index.html`, `books.html`, `publications.html`, or `profile.html` and refresh.
- Shared styling (colors, type, layout) lives in `assets/css/main.css`.
- Book cover images are in `assets/img/`; replace them with the same filenames to update covers without touching the HTML.
- The site brand ("Python for Engineers & Scientists" / `#python4tech`) appears in the header and footer of every page — update it in each file if it changes.

## License

Site code is available under the MIT License (see `LICENSE`). Book cover artwork and book/author content are © Mudassar Hussain Hashmi — all rights reserved.
