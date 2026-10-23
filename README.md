# Qix · Notes

A bilingual personal blog about voice interaction, research, and engineering.

## Preview locally

No build tools or dependencies are required. Run a local static server from the project directory:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Pages

- `index.html` — bilingual home page
- `full-duplex.html` — Chinese article: “What Is Full Duplex?”
- `full-duplex-en.html` — English edition

Use the language switch in the header to change languages. The selected language is saved in the browser.

## Deployment

This is a static site and can be hosted with GitHub Pages. In the repository settings, enable **Pages** and deploy from the `main` branch. The site uses relative page links, so it also works as a project site under a repository path.

## License

Content and code in this repository are provided for personal reading. Please contact the author before republishing the articles.
