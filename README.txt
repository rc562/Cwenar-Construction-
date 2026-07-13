Cwenar Construction — hosting build
===================================

Contents (this folder is the whole site):
  index.html            the site
  support.js            runtime the page needs (do not delete)
  assets/cwenar-logo.png

Deploy — GitHub + Netlify
1. Make a new GitHub repo (e.g. cwenar-site). Upload the CONTENTS of this
   folder to the repo root — index.html must sit at the top level.
2. On netlify.com: Add new site → Import an existing project → pick the repo.
   Build command: (leave empty)   Publish directory: (leave as root)
3. Deploy. Netlify gives you a temporary URL; add the real domain under
   Site settings → Domain management when ready.

Notes
- The contact form is front-end only right now (shows a confirmation but
  does not send email). Netlify Forms can make it deliver for free — small
  markup change; ask Claude when you're ready.
- Updating the site later: replace index.html in the repo, Netlify
  redeploys automatically.
