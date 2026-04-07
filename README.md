# GitHub Pages Experiments

This repository is a workspace for experimental standalone web pages.

## Structure

- `index.html`: entry page for published experiments.
- Root-level `*.html` files should stay self-contained unless a specific experiment needs its own folder.
- Larger experiments should use a dedicated top-level folder with their own assets and README.

## Local Preview

For simple HTML files, open the file directly in a browser or run a static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages Setup

Recommended repository for a user site:

```bash
git remote add origin https://github.com/bzbj/bzbj.github.io.git
git push -u origin main
```

In GitHub:

1. Open the repository settings.
2. Go to Pages.
3. Set the source to `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save.

The site will publish at:

```text
https://bzbj.github.io/
```

For a project site instead, create another repository name and use:

```bash
git remote add origin https://github.com/bzbj/<repo-name>.git
git push -u origin main
```

The project site URL will usually be:

```text
https://bzbj.github.io/<repo-name>/
```
