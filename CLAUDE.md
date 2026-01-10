# rohitwpillai.github.io

Personal academic website for Rohit Pillai.

## Tech Stack

- **Framework**: Quarto
- **Styling**: Custom SCSS + Quarto themes
- **Hosting**: GitHub Pages (via GitHub Actions)

## Local Development

```bash
# Preview site
quarto preview

# Build site (outputs to _site/)
quarto render
```

## Project Structure

```
_quarto.yml      # Site configuration (navbar, theme, metadata)
index.qmd        # Homepage
cv.qmd           # CV page
team.qmd         # Team/group page
research.qmd     # Research interests
publications.qmd # Publications list
styles.css       # Custom styles
```

## Deployment

GitHub Actions workflow (`.github/workflows/publish.yml`) automatically:
1. Builds the site with `quarto render`
2. Deploys to `gh-pages` branch
3. Serves via GitHub Pages

## Fonts

- Headings: Fraunces (serif)
- Body: Default Quarto fonts

## Hidden Pages

Teaching and Blog tabs are currently hidden (commented out in `_quarto.yml`).
