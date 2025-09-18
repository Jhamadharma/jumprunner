
# Jump Runner (HTML5)

A single-file web game. Open `index.html` locally or host it anywhere that serves static files.

## Quick publish options

### 1) GitHub Pages (free)
- Create a new repo (e.g., `jump-runner`).
- Upload `index.html` to the repo root.
- In **Settings → Pages**, set **Branch: main** and **Folder: /root**. Save.
- Your site will appear at `https://<your-username>.github.io/jump-runner/`.

### 2) Netlify Drop (free)
- Go to https://app.netlify.com/drop
- Drag & drop the folder or this ZIP.
- Netlify gives you a live URL instantly. You can also connect a custom domain.

### 3) Vercel
- Import the repo at https://vercel.com/new
- Vercel detects it as static and deploys. Auto-HTTPS + custom domains.

### 4) itch.io (great for games)
- Create a new project → **Kind**: HTML.
- Upload this ZIP, check **“This file will be played in the browser”**.
- Publish. Done.

## Notes
- The entry file must be named `index.html` for most hosts.
- No build tools or backend are required.
