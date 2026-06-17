# Publish this package with GitHub Pages

Repository: `Vikrantthenge/vikrant-portfolio`

## 1. Upload the files

Open the repository on GitHub and select **Add file → Upload files**.

Upload the contents of this package into the repository root:

- `.nojekyll`
- `index.html`
- `ai-ops-assistant-showcase.html`
- `README.md`
- `4_Project_Summaries/AI-Powered-Operations-Intelligence-Assistant.md`

Do not upload the ZIP file itself. Upload the files and folder inside it.

Use this commit message:

`Add AI operations assistant GitHub Pages showcase`

Commit directly to the `main` branch.

## 2. Enable GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages** under **Code and automation**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Select branch `main` and folder `/(root)`.
5. Select **Save**.

## 3. Verify deployment

Open:

- Portfolio root: `https://vikrantthenge.github.io/vikrant-portfolio/`
- Direct showcase: `https://vikrantthenge.github.io/vikrant-portfolio/ai-ops-assistant-showcase.html`

The root page redirects to the project showcase. The direct showcase URL is the link used in the README.

## 4. Troubleshooting

Check the repository **Actions** tab for the `pages build and deployment` workflow. A green check means deployment succeeded. A failed workflow contains the specific error.
