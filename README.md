# Miriam Bosibori — Portfolio (ATLAS)

Personal portfolio site for Miriam Bosibori, Digital Marketing Strategist (Doha, Qatar).
Built with React + Vite. Single-page site with case studies, an embedded CV, and a
Formspree-powered contact form.

## Run locally
```bash
npm install
npm run dev      # opens a local dev server (usually http://localhost:5173)
```

## Build for production
```bash
npm run build    # outputs static files to /dist
npm run preview  # preview the production build locally
```

## Deploy (Vercel)
1. Push this folder to a GitHub repository.
2. In Vercel, "Add New Project" and import the repo.
3. Vercel auto-detects Vite. Defaults are correct:
   - Framework Preset: **Vite**
   - Build Command: **npm run build**
   - Output Directory: **dist**
4. Click **Deploy**.

## Notes
- Contact form posts to Formspree (form id `xrpzrbjz`). On the first live
  submission, Formspree emails you once to confirm the form. After that,
  messages arrive at miriambosibori29@gmail.com.
- The CV and all images are embedded in the code, so there are no extra
  files to host.
