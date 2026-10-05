# Freddie Manyate — Technical Portfolio

A responsive, five-page static portfolio built with HTML, CSS and JavaScript. No installation or build step is required.

## Files

- `index.html`: Home.
- `projects.html`: Projects.
- `code.html`: Code samples.
- `expertise.html`: Expertise.
- `profile.html`: Profile.
- `assets/styles.css`: colours, typography, responsive layout and print styles.
- `assets/script.js`: project category filters.
- `.nojekyll`: serves the site as plain static files on GitHub Pages.

## Preview

Open `index.html` in your browser, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages

1. Create a repository named `technical-portfolio` under your GitHub account.
2. Extract this ZIP. Upload the contents of the extracted folder to the repository root: all five HTML files must be at the root, with the `assets` folder alongside them.
3. Commit the uploaded files to `main`.
4. In the repository, open Settings > Pages. Under Build and deployment, select Deploy from a branch, then `main` and `/ (root)`, and save.
5. Once deployment completes, use the URL shown by GitHub Pages. For account FreshDaDon and repository technical-portfolio, the expected URL is https://freshdadon.github.io/technical-portfolio/.

Alternatively, use a repository named `FreshDaDon.github.io` for an account homepage.

## Editing

Update content in the relevant HTML file. Shared navigation appears in each page; update all five files when changing navigation links. Change the CSS variables at the start of `assets/styles.css` to customise the palette. Project filters use matching `data-filter` and `data-category` values.

## Content notes

The content comes from the supplied technical portfolio. Private repository links require the appropriate repository access. No contact email, mobile number or LinkedIn address was supplied in that document. Add these if desired. Two original Django excerpts are displayed as portfolio evidence; they are not executable parts of this website.

Review the excerpt in the access-control sample before using it in an application: its `context` assignment ends with a comma, which creates a tuple rather than the dictionary expected by Django's `render`. The supplied excerpt is preserved here for fidelity to the source document.

GitHub Pages publication makes the portfolio available according to GitHub's hosting access settings; this is separate from the private ChatGPT-hosted version.

## Profile sources

Profile content was updated from the supplied UCT CV, motivation letter and professional profile PDF. Employment dates follow the CV. DIRISA 2022 placement is omitted because the CV and profile state different results. AWS entries are training courses, not claims of professional certification. Certificate documents and verification links were not supplied. Referee details are excluded.
