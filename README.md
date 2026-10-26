# MOVEA — FeLiya Design

Conceptual fitness & wellness portfolio website. Final approved typography version.

## Deployment to Vercel

This repository uses a single static HTML page at `public/index.html` and a `vercel.json` configuration with `outputDirectory: "public"`.

1. Import this GitHub repository into Vercel.
2. Framework Preset: **Other**. Root Directory: `./`.
3. Build Command: leave unset. Output Directory: `public`.
4. Deploy.

The photographs and graphics needed for the page are embedded inside the HTML itself. The two Flow animation videos are streamed from Cloudinary and require an internet connection. The contact form is a **portfolio demonstration** and does not send submissions.

## Before sharing the deployed URL

- Replace `YOUR-DOMAIN.example` inside `public/index.html` with the actual HTTPS URL, especially for `og:url` and `og:image`.
- Upload the separately prepared 1200×630 social preview image as `public/movea-og-1200x630.jpg` for social previews.
- Add the prepared favicon and Apple Touch Icon files to `public/` if desired.
- Test both videos, navigation, contact form demo, responsive layouts, and the preview metadata.

Design: FeLiya Design, 2026. MOVEA is a fictional portfolio concept, not an operating fitness club.
