# Token Guide

A step-by-step guide for using design tokens with Claude Code MCP to build Figma button components with real variable bindings.

**Sequel to:** [I Spent 3 Days Failing at This So You Can Do It in 30 Minutes](https://figma-guide-toec.vercel.app/)

## What this covers

- Creating two-layer design tokens (primitive + semantic) as JSON
- Importing tokens into Figma via Token Studio
- Using Claude Code + MCP to build button components
- Writing a Figma plugin to bind variables to components
- Creating a component set with variant properties

## Deploy

Static site — just HTML, images, and one video. No build step.

### Vercel

```bash
npm i -g vercel
vercel
```

### Netlify

Drag and drop this folder into [Netlify Drop](https://app.netlify.com/drop).

### GitHub Pages

Push to a repo, go to Settings → Pages → Deploy from branch → `main` → `/ (root)`.

## Files

```
index.html                 Main guide page
demo-video.mov             Screen recording of the workflow
token-studio-export.png    Token Studio screenshot (Step 2)
test-button-result.png     Single test button result (Step 4)
all-buttons-bound.png      All buttons with variables bound (Step 9)
component-set-result.png   Component set with variants (Step 10)
```

## Author

[Seeon Kim](https://seeonk.com)
