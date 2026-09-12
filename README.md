# HSK Contract Watchdog landing page

Static English landing page for the hackathon disclosure concept. This is presentation content, not a working registry, authentication system, or disclosure backend.

## Publish on Vercel

Import this directory as a Git repository in Vercel, choose Framework Preset **Other**, leave Build Command empty, and set Output Directory to **dist**. The included vercel.json sets the output directory automatically.

Alternatively, with the Vercel CLI installed, run `vercel --prod` from this directory and follow the account prompts.

## Local preview

Run `python3 -m http.server 4173 --directory dist` from this directory.

Content: dist/index.html. Styling: dist/style.css. Google Fonts is optional; system fonts are used if unavailable.

No wallet requests, tracking, forms, private findings, or credentials are included.
