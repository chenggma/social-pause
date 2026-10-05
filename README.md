# Social Pause

Prototype 0.1 of a short-session practice game: notice → pause → consider the other person → act or ask.

- `app/` — the game (single HTML file + PWA manifest, service worker, icons). This folder is what GitHub Pages serves.
- `main.js` — Electron wrapper for the local Mac app.

```bash
npm start            # run the Mac app in dev mode
npm run package      # build dist/Social Pause-darwin-arm64/Social Pause.app
```

On iPhone: open the web link in Safari → Share → Add to Home Screen.
On a phone, long-press the "Social Pause" title for 0.8 s to show the facilitator panel.
