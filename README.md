# Opera Tracker PWA

This package is ready for GitHub Pages.

## Files
- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `icons/`

## Deploy on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files in this folder, preserving the `icons` folder.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/ (root)`
5. Save. GitHub Pages will publish the site.

## Notes
- The app stores data in the browser with localStorage.
- Export your data regularly if you want backups across devices.
- The service worker enables installability and basic offline caching.
