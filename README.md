# DAIVITECH — Premium website

A responsive static website built around the positioning:
**Creative. Media. Technology. | Business Challenges. Connected Solutions.**

## Included
- `index.html` — all website sections and metadata
- `styles.css` — responsive design system
- `script.js` — mobile navigation, year and enquiry mailto form

## Before launch
1. Confirm `hello@daivitech.com` is an active mailbox. If not, replace it in `index.html` and `script.js`.
2. Add verified phone/WhatsApp, social links and business address only if you want them public.
3. Add actual portfolio projects when available. No fictional client logos, testimonials or results are included.
4. Replace the typographic D monogram with your approved final vector logo when ready.
5. Review all service descriptions to ensure they match what you can actually deliver, including through disclosed production partners.

## Free deployment with Cloudflare Pages
1. Create a GitHub repository and upload `index.html`, `styles.css`, and `script.js` to the repository root.
2. In Cloudflare Dashboard, go to Workers & Pages → Create → Pages → Connect to Git.
3. Select the repository. Choose framework preset `None`.
4. Leave build command blank and set build output directory to `/`.
5. Deploy. Test the `*.pages.dev` URL.
6. In the Pages project, add `daivitech.com` and `www.daivitech.com` under Custom domains.
7. Follow the DNS instructions shown by Cloudflare at your registrar. Preserve existing MX records if domain email is configured.

The website is static: no server, database, paid plugins or build step required. The contact form opens the visitor's email app; it does not store submissions. Cloudflare free-plan terms and limits can change.
