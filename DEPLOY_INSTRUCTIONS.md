# Correct GitHub Pages Deployment

This package is designed to be added to the existing `vikrant-portfolio` repository
without replacing the repository's current README.md or index.html.

## Upload only these files

- `ai-ops-assistant-showcase.html`
- `AI-OPS-ASSISTANT.md` (optional project documentation)

## Do not replace

- Existing `README.md`
- Existing `index.html`
- Existing portfolio folders or assets

## Steps

1. Open: `https://github.com/Vikrantthenge/vikrant-portfolio`
2. Click **Add file** → **Upload files**
3. Upload the two files from this package.
4. Commit with:
   `Add AI operations assistant showcase`
5. In **Settings** → **Pages**, confirm:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**

The project page will be:

`https://vikrantthenge.github.io/vikrant-portfolio/ai-ops-assistant-showcase.html`

## Optional README update

Add only this project entry to your existing repository README.md:

### AI-Powered Operations Intelligence Assistant

Local Generative AI assistant using Ollama, Docker and Open WebUI to explore
prompt-engineered workflows for operational risk analysis, KPI assessment and
executive-style reporting.

**Live showcase:** [View project](https://vikrantthenge.github.io/vikrant-portfolio/ai-ops-assistant-showcase.html)  
**Project notes:** [Read documentation](AI-OPS-ASSISTANT.md)
