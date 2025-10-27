# Let-s-study-
Study planner!
```markdown
# Let's Study ✨! — Study Planner Web App

A lightweight, client-side study planner web app with goals, to-dos, notes, timers, progress tracking, theme switching, motivational quote of the day, notifications, and a simple music player (upload your own). Built as a single static `index.html` file — easy to run locally or publish to GitHub Pages / Netlify / Vercel.

## Features
- Daily Goals & To‑Do lists with add / edit / delete
- Mark items as done (strike-through)
- Auto-save to `localStorage` (lists, notes, theme)
- Progress bars for goals and to-dos
- Custom study/break timer with browser notifications
- Theme switcher (Light / Dark) — remembers preference
- Quote of the Day shown on the welcome (start) page
- Notes with auto-save + Export notes (.txt)
- Music player: upload and play local audio files (session only)
- Single-file: `index.html` (no build step)

## Files
- `index.html` — the full app (place assets in same folder if needed)

## Getting started (Run locally)
1. Save `index.html` into a folder.
2. Open the file in your browser:
   - Double-click `index.html` or right-click → Open with → Your browser.
   - For best experience (notifications and some APIs), serve via a local HTTP server.

Optional: run a simple static server (recommended)
- Python 3:
  - cd to folder and run:
    - `python -m http.server 8000`
  - Open `http://localhost:8000` in your browser.
- Node.js (http-server):
  - `npx http-server -p 8000`
  - Open `http://localhost:8000`

## Publish / Deploy
You can host this static app with any static-hosting provider.

### GitHub Pages
1. Create a new GitHub repo and add `index.html`.
2. Commit and push.
3. Go to the repo → Settings → Pages → Source → choose branch `main` (root).
4. Save. Your site will be at:
   `https://<your-username>.github.io/<your-repo>/`

## Notes & Browser Behavior
- Notifications: browsers require permission. If denied, the app falls back to `alert()`. GitHub Pages / Netlify use HTTPS which is needed in some browsers for notifications.
- Music Upload: For security, browsers don't persist uploaded files across sessions; uploaded music plays while the tab is open. If you need persistent music hosting, use a hosted audio file or a streaming service embed.
- localStorage: Saves lists, notes, and theme locally per browser & origin (not synced across devices).

Enjoy studying! ✨📚🎵
```
