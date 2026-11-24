# Soccer Game Stats Tracker

A mobile-friendly React app for recording soccer player statistics separately for each half. Data is stored locally in the browser and can be exported/imported as JSON.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `soccer-game-stats`.
2. Upload all files from this repository package to the repository root.
3. Ensure the default branch is named `main`.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **GitHub Actions**.
6. Open the **Actions** tab and wait for **Deploy to GitHub Pages** to finish.
7. The app URL will be shown in the completed deployment and in **Settings → Pages**.

Typical URL: `https://YOUR-USERNAME.github.io/soccer-game-stats/`

## Use on iPhone

Open the published URL in Safari, tap **Share**, then **Add to Home Screen**.

## Local development

```bash
npm install
npm run dev
```

## Notes

- Game data is stored only in the current browser/device using `localStorage`.
- Use **Export** for backups or to transfer a game to another device.
- The included service worker provides basic offline caching after the first successful visit.
