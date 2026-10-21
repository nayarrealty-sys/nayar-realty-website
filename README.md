# Nayar Realty — GitHub migration base

This package was prepared from the current production site at `nayarrealty.vercel.app`.

## What is preserved
- Current public content and section structure.
- Current property catalog as exposed on the production page.
- Current production imagery, referenced from the existing Vercel project.
- Stable domain selected for QR: `https://nayarrealty.com.mx/`.

## Exact backup
The exact current production deployment remains immutable in Vercel:
- Project: `v0-nayar-realty-website`
- Project ID: `prj_eR7DnrKe3Ir063ljnPZYf08I3AiV`
- Deployment ID: `dpl_2TEUakLCXAmS7VMMdJwx4PBmjGTM`

Do not delete the original Vercel project until the local image assets have been migrated and the GitHub version has been verified.

## GitHub publication
1. Create a public repository, recommended name: `nayar-realty-website`.
2. Upload `index.html` from this package.
3. Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main`.
6. Folder: `/(root)`.
7. Save.
8. Test the generated GitHub Pages URL.
9. Only after verification, migrate the custom domain.

## Custom domain and QR
The QR in `/qr` points to:
`https://nayarrealty.com.mx/`

The QR does NOT need to change when the website changes. As long as this domain stays the public destination, the printed QR remains valid.

## Important migration note
The current GitHub base references production images on `nayarrealty.vercel.app`.
This is intentional for the first migration step so the visual assets remain unchanged.
Before deleting the Vercel project, move those image assets into the GitHub repository and replace their URLs with local paths.

## Next phase
Once this base is published, ChatGPT can revise:
- branding and hero,
- property inventory,
- SEO,
- mobile layout,
- forms / WhatsApp,
- language switching,
- individual property pages,
- analytics and campaign links.
