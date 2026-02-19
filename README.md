# paramountcap.org

Static site ready for Vercel deployment.

## Local preview

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to Vercel

1. Push this repository to GitHub/GitLab/Bitbucket.
2. Import the project in Vercel.
3. Keep defaults (Framework Preset: **Other**).
4. Deploy.

The `vercel.json` file routes all paths to `index.html`, so the single-page site can be loaded from any route.
