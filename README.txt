REDDIT RANDOM - SAFARI WEBPAGE

This is a static HTTPS website version of Reddit Random.

FILES
- index.html
- manifest.webmanifest
- sw.js

HOW TO USE
1. Upload all three files to any static HTTPS web host.
2. Open the resulting HTTPS address in Safari on your iPhone.
3. Tap Import and choose a COPY of saved_items.json from Files/iCloud Drive.
4. Safari stores the imported library in browser storage.
5. Optional: Safari Share -> Add to Home Screen.

GOOD STATIC HOST OPTIONS
- GitHub Pages
- Cloudflare Pages
- Netlify
- Any normal HTTPS web hosting account

No server-side code, database, Reddit API key, or Windows connection is required.

IMPORTANT
The iPhone/Safari version is completely separate from the Windows Reddit Random app.
It only reads the JSON copy you manually import.

The service worker caches only the local webpage shell. Reddit images/videos still
load from their normal internet locations.
