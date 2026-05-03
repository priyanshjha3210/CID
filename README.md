# CID Chase

Static browser game packaged for Vercel.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, import the repository.
3. Keep the framework preset as `Other`.
4. Leave the build command and output directory empty.
5. Deploy.

The app is served from `index.html`. Game code and game assets are embedded in that file; the bottom ad banner loads its provider script from `highperformanceformat.com`.

## Optional CLI Deploy

```powershell
npm i -g vercel
vercel --prod
```
