# AeroStaff v4.0

Aircraft maintenance manpower planning and scheduling system for TMBA teams.

## Deployment

### GitHub Pages
This project is ready to be hosted on GitHub Pages.
1. Go to the repository settings on GitHub.
2. Navigate to "Pages".
3. Under "Source", select "Deploy from a branch".
4. Select the `main` branch and the `/root` folder (or just `/` if that's the option).
5. Save.

The site is a static application located in the `public` folder. If GitHub Pages requires the index.html to be in the root, you may need to move the contents of `public` to the root directory, or configure GitHub Pages to serve from `public` if supported (usually it supports root or docs).

**Recommended for this structure:**
Configure GitHub Pages to build from the `public` folder if using a CI/CD, or simply move the contents of `public` to the root if you want the simplest Launch setup.

### Local Usage
You can serve the `public` folder using any static file server.
If you have Node.js installed, `index.cjs` appears to be a server script included with the build:

```bash
node index.cjs
```
