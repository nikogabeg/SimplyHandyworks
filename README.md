# Simply Handyworks

Single-page site for Simply Handyworks (George Galedo, General Contractor).

- `index.html` — the full site (no build step, no dependencies)
- `main_logo.png` — logo, referenced by `index.html`, must stay in the same folder

## Request form
The "Request a Free Quote" form submits to `Simplyhandyworks@gmail.com` via [FormSubmit](https://formsubmit.co) — a free, backend-free form relay. **The first submission after this goes live will trigger a one-time confirmation email to that inbox — click "Activate Form" in it, or all future submissions will be silently dropped.**

## Hosting with GitHub Pages
1. Go to the repo's **Settings → Pages**
2. Under "Build and deployment," set **Source** to `Deploy from a branch`
3. Set **Branch** to `main`, folder `/ (root)`, then Save
4. The site will publish at `https://nikogabeg.github.io/SimplyHandyworks/` within a minute or two
