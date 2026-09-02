# Mihai Surdeanu — academic homepage

A responsive, single-page academic website for `MihaiSurdeanu.github.io`. Plain HTML and CSS; no JavaScript, framework, package installation, or build step. The desktop content area is 960px wide, with a portrait at the upper right and a stacked layout on small screens.

## Repository structure

```text
MihaiSurdeanu.github.io/
├── index.html
├── style.css
├── .nojekyll
├── .gitignore
├── README.md
├── images/
│   ├── photo-placeholder.svg
│   └── README.md
├── papers/
│   └── README.md
└── files/
    └── README.md
```

## Preview

Open `index.html` in a browser. All navigation and styling work locally.

## Replace the placeholders

- Add your portrait to `images/` and update the image source and alternative text in `index.html`.
- Replace each publication's bracketed title, authors, venue, and year. Add PDFs to `papers/`, then replace the PDF and code placeholder spans with real links. Duplicate or remove publication articles as needed.
- Fill in the current and former student lists.
- Replace the teaching entries with actual semesters, course numbers, and titles. Link course titles when a course page is available.

All missing content is explicitly labeled. PDF and code placeholders are plain text rather than broken links. No student names, courses, or publications have been invented.

## Upload to GitHub Pages

1. Create a public repository named **MihaiSurdeanu.github.io** under the **MihaiSurdeanu** account, or use that repository if it already exists.
2. Upload the contents of this folder to the repository root. `index.html` must be at the root, not inside another `MihaiSurdeanu.github.io` folder. Include `.nojekyll` if uploading with Git; it explicitly disables Jekyll processing.
3. In the repository's **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/ (root)**, and save.
4. Once GitHub finishes publishing, visit https://MihaiSurdeanu.github.io/.

See the [official GitHub Pages instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) if your repository settings differ.

## Maintain the site

Edit content in `index.html` and presentation in `style.css`. Colors are defined at the top of the stylesheet. The homepage navigation links to sections of the same page. Keep filenames and link capitalization identical when adding assets; GitHub Pages paths are case-sensitive.
