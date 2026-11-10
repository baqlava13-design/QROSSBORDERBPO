# Qrossborder — Vercel-ready website

## Start

1. Upload this project to a GitHub repository (files at repository root).
2. Import the repository into Vercel.
3. Framework preset: Vite. Build command: `npm run build`. Output: `dist`.
4. Deploy to a temporary Vercel URL and test all four pages.
5. Add `qrossborder.com` and `www.qrossborder.com` under Vercel project Domains and follow Vercel's displayed DNS instructions. Preserve MX/SPF/DKIM records for existing email.

## Important before acquisition

- The contact form currently opens the visitor's email application with a prefilled message to `info@qrossborder.com`; it is **not** a server-side submission. Confirm this address works. Replace with a verified form backend (e.g. a properly configured email API / CRM) before relying on unattended lead capture.
- Verify business details, privacy policy and data-processing arrangements before launch.
- Prices: Starter 8 h/mo × €34.99 = €279.92; Growth 20 h/mo × €32.49 = €649.80; Dedicated 40 h/mo × €29.99 = €1,199.60; excl. VAT.
- The illustrations are CSS/vector, not photographs or testimonials. Original user-provided logo is included.
- All four pages are included: `/`, `/ecommerce-operations/`, `/customer-support/`, `/finance-administration/`.
- `vercel.json` routes deep links to the React application.


## Photography update
This edition includes five local WebP image assets in `public/images/` (no external image hosting required). The images are illustrative AI-generated design imagery, not photographs of actual Qrossborder personnel or premises. All original Dutch copy and the three pricing tiers are preserved.

## GitHub upload
Upload the **contents** of this folder, preserving `src/` and `public/` directories. Remove outdated duplicate root-level `main.jsx`, `style.css`, and `logo.png` if present. Do not upload the ZIP as the deployed source.
