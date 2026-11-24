# Noor Faisal Portfolio

Single-page static site: `index.html` + `assets/` (photo `noor-faisal.jpg`, `favicon.png`). No backend, no paid services.

## Editing
- All text, CSS and JavaScript are in `index.html`. Search for the text you want to change.
- Services, process, FAQ, "why" cards and the three demo sites are data arrays near the top of the `<script>` (`svc`, `D`).
- Colours and spacing are CSS variables in `:root` (main site) and `.dm`, `.dm.oc`, `.dm.gh` (demos; `bn` uses `.dm` defaults).
- After publishing, replace `YOUR-GITHUB-USERNAME` in the canonical link with your real username.

## Replacing images
Replace `assets/noor-faisal.jpg` with a new file of the same name (square, ~900px, under 300 KB). Demo "gallery" tiles are labelled placeholders; to use real images, put files in `assets/demo-images/` and swap the tile for `<img src="assets/demo-images/x.jpg" width="800" height="600" loading="lazy" alt="...">`.

## Publish free on GitHub Pages (Android)
1. Open https://github.com/ and sign in or create a free account.
2. Create a **public** repository named `noor-faisal-portfolio`.
3. Unzip the project on your phone, then upload `index.html`, `README.md` and the whole `assets` folder (Add file > Upload files). `index.html` must be in the repository root. Do not upload only the ZIP.
4. Open the repository **Settings**, then **Pages**.
5. Under Source choose **Deploy from a branch**.
6. Choose Branch `main` and folder `/ (root)`, then **Save**.
7. Wait a few minutes. Your address will look like `https://YOUR-GITHUB-USERNAME.github.io/noor-faisal-portfolio/`. It is only live once GitHub shows it as published.
8. Test on your phone: menu, demos, Back to Main Portfolio, contact form, copy button.
9. To update later, upload the changed files again with the same names.

Notes: GitHub Pages hosts static sites only (no form processing). A custom domain is not free to register but can be connected later. Check https://docs.github.com/en/pages/quickstart for current limits. An alternative free static host is Cloudflare Pages or Netlify; check their current free-plan limits.

## Outreach message
Hello,

I'm Noor Faisal, an independent website designer.

I've created a portfolio where you can explore my website design approach and sample business website concepts.

Portfolio:
[INSERT ACTUAL LIVE LINK]

I also offer a complimentary homepage design concept to selected businesses, with no obligation to proceed.

If you're considering improving your business's online presence, I'd be happy to discuss an idea tailored to your business.

Best regards,
Noor Faisal
Independent Website Designer
jihadahmed9726@gmail.com
