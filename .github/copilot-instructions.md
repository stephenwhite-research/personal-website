# Project

This is a dependency-free static personal website for GitHub Pages. The page
is authored in `index.html`, with styling in `styles.css` and image assets in
`media/`. Keep it deployable from the repository root without a build step.

# Validation

- Check whitespace and patch formatting with `git diff --check`.
- Preview locally with `python3 -m http.server 8000` and open
  `http://localhost:8000`.
- There is no test runner, build, or lint command configured.
