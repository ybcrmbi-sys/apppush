# App Push Mockup Generator

Vercel static deployment package for `앱푸시 시안 생성기.html`.

## Structure

- `index.html`: Vercel entry file copied from the original HTML.
- `앱푸시 시안 생성기.html`: Original working file.
- `vercel.json`: Static deployment settings.
- `bg_img/`, `logo/`, `templates/`: Local assets and template data kept with the project.

## Deploy With Vercel CLI

```powershell
npm i -g vercel
vercel login
vercel deploy --prod
```

## Deploy With Git

Push this folder to a Git repository and import it from the Vercel dashboard.

Use these settings:

- Framework Preset: `Other`
- Build Command: leave empty
- Output Directory: leave empty
- Install Command: leave empty

