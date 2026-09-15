# LedgerList marketing site

This folder contains a dependency-free static marketing page for LedgerList. All URLs are relative, so the site works from a GitHub Pages project subpath.

## Preview locally

From the repository root:

```bash
python3 -m http.server 4173 --directory marketing
```

Then open `http://127.0.0.1:4173/`.

## Publish with GitHub Pages

Configure GitHub Pages to deploy this folder, or copy its contents into the branch/folder used by the repository's Pages workflow. No build step is required.
