# Restaurant Shotlist by Zentrik Digital — MVP v1.0

A mobile-first, no-account-needed restaurant filming checklist.

## Included
- Restaurant/project name, type and shoot date
- Six shoot objectives, including a quick-shoot challenge
- Prebuilt checklist templates grouped by category
- Check-off progress tracking
- Add custom shots and remove custom shots
- Copy a shoot for a new visit
- Export a plain-text checklist
- Local browser storage (no backend/API required)
- PWA manifest and SVG icon

## Run locally
Open `index.html` in a modern browser. For best PWA behavior, serve over localhost or HTTPS.

## Free deployment option
1. Create a GitHub account and a new public repository named `zentrik-shotlist`.
2. Upload all files in this folder to the repository root.
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch; select `main` and `/ (root)`; Save.
5. Wait for GitHub Pages to publish and open the provided `https://YOUR-USERNAME.github.io/zentrik-shotlist/` address.

Alternative: deploy the folder to a static hosting provider such as Cloudflare Pages or Netlify. No build command is needed; publish directory is the project root.

## Important MVP limitation
This version saves data in the current browser/device only. It does not have cloud sync, user accounts, team sharing, a server database or AI-generated shots. Those require creating and configuring external accounts and adding credentials securely. Do not put private API keys in frontend files.


## Cinematic shot library update
This version expands the shot library with 100+ shot prompts covering multiple food angles, push-ins, pull-backs, overheads, macro texture, drinks, snacks and pastry reveals, cooking-process coverage (including safe wok/stove action), customer moments, promotions, packaging, natural sound, slow motion, and edit safety shots. Selecting Quick Shoot Challenge by itself creates a short list; selecting it alongside other objectives no longer truncates the full checklist.
