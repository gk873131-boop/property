# Braj Aangan — React + Vite

A complete responsive React landing website for exploring property opportunities in Vrindavan, with an original brand identity, navy/teal/coral palette, large photographic hero, scroll-reveal motion, mobile navigation, opportunity cards, site-visit journey, and enquiry-to-WhatsApp form.

## Run locally

1. Install Node.js (18+ recommended).
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL shown by Vite.
4. Run `npm run build` for a production build.

## Deploy on Vercel

Import this repository into Vercel and keep the project root at this folder. The included `vercel.json` sets the Vite framework, `npm run build` command, and `dist` output directory. Use Node.js 22.x in the Vercel project settings; the current Vite toolchain requires Node.js 20.19+ or 22.12+.

## Before launch

- Replace `WA_NUMBER` in `src/main.jsx` with the verified WhatsApp number, in international format without `+`.
- Replace illustrative photo URLs in `src/main.jsx` with licensed/approved property photographs.
- Verify all property details, location, pricing, title and approvals before publishing. The page intentionally avoids invented property prices and guarantees.
- Google Fonts and the illustrative Unsplash photos load over the internet.
