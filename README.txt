PHYSICAL EVOLUTION v0.2 — PWA setup

Files: index.html, manifest.json, sw.js, and icons/

Publishing on GitHub Pages:
1. Upload/replace the files in the repository root.
2. Keep the Pages source on branch main and folder /(root).
3. Wait for the Pages deployment to finish.
4. Open the published URL in Chrome over HTTPS.
5. Use Chrome menu > Install app if available.

Data safety:
- The app stores records in browser localStorage on the current origin.
- Changing from a local file to GitHub Pages creates a separate storage area.
- Keep JSON backups before updating or clearing browser data.
- This version keeps the existing localStorage key in index.html.

The icon files are provided in icons/.
