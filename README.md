# Andrea Cervantes — Engineering Portfolio Starter

A minimal, responsive, multilingual (English / Spanish / Dutch) static portfolio designed for GitHub Pages.

## What's included

- `index.html` — homepage
- `projects/thesis.html` — starter case study for your master's thesis
- `assets/css/style.css` — all visual styling
- `assets/js/main.js` — language selector and mobile menu
- Responsive layout for desktop and mobile
- No build tools, package installation, or paid services required

## Before publishing

1. Replace `YOUR.EMAIL@example.com` in `index.html` with your professional email.
2. Replace `https://www.linkedin.com/` with your actual LinkedIn profile URL.
3. Add your CV PDF to `assets/docs/andrea-cervantes-cv.pdf` (create the `docs` folder if needed), or update the CV link.
4. Replace the conceptual thesis graphic with a real figure from your thesis when ready.
5. Review all text in English, Spanish and Dutch. The current text is a draft and some project sections are placeholders.
6. Only claim skills, methods and results that accurately represent your experience.

## How to preview it on your computer

The easiest way is to open `index.html` in a browser. The homepage should work without installation. Some browsers may restrict local storage when opening files directly, but the language selector itself should still work.

For a more reliable preview, you can use Visual Studio Code with the Live Server extension, but that is optional.

## Publish with GitHub Pages

1. Create or sign in to a GitHub account at https://github.com/.
2. Create a **public** repository named exactly `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
3. Upload all files and folders from this starter package to the repository root. Do not upload only the ZIP file.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then save.
7. Wait for the deployment to finish. Your site should be available at `https://YOUR-USERNAME.github.io/`.

GitHub's interface can change. If a setting looks different, consult the official Pages guide: https://docs.github.com/en/pages

## How to update the website later

Edit the relevant file and commit the changes:
- Text and links: `index.html` or `projects/thesis.html`
- Colors, spacing, typography and layout: `assets/css/style.css`
- Translations and language behavior: `assets/js/main.js`

Every time you push or commit changes to the published branch, GitHub Pages rebuilds the site.

## Language selector

The header selector switches among `EN`, `ES` and `NL`. The selected language is remembered in the visitor's browser. The homepage text is held in `assets/js/main.js`; the thesis case-study translations are currently embedded in `projects/thesis.html`.

For future projects, use the same translation pattern or move each language into its own page if you want language-specific URLs and better search-engine indexing.
