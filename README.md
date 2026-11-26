# GYA EDM images

Public image hosting for GYA client email campaigns, served by Vercel.

## Structure

```
<client-slug>/<yyyy-mm>-<campaign-slug>/<image>
```

Example: `melville/2026-11-end-of-year/hero-family.jpg`
becomes `https://<vercel-domain>/melville/2026-11-end-of-year/hero-family.jpg`

## Rules

- Images only. This repo is public, so never commit patient lists, HTML with private data or anything confidential.
- Never overwrite or delete a folder for an email that has been sent, because the email still loads its images from here.
- Start each new campaign in a new folder.
