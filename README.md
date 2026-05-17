# Daisy Treats

This is the standalone Daisy Treats static website.

## Deployment

This repository is configured for Render using `render.yaml`.

### To publish to GitHub

1. Create a new GitHub repository in your account.
2. Add the remote and push from this folder:

```bash
cd daisy-treats
git remote add origin <your-github-repo-url>
git push -u origin master
```

### Render setup

1. Go to https://dashboard.render.com
2. Create a new Static Site or Web Service
3. Connect this GitHub repository
4. Use the default build settings
5. Deploy

## Contents

- `index.html` — site markup
- `styles.css` — styles
- `app.js` — client interaction
- `render.yaml` — Render deployment config
