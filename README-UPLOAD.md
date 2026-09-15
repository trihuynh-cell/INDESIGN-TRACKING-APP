Upload these files to replace on:
https://github.com/trihuynh-cell/INDESIGN-TRACKING-APP

Required:
  icon-192.png          (true 192x192)
  icon-512.png          (true 512x512)
  apple-touch-icon.png  (180x180)
  icon-32.png
  manifest.json         (?v=3 cache-bust)
  sw.js                 (CACHE = indd-tracking-v3)
  index.html            (icon links ?v=3)

After upload:
1. Open site → DevTools → Application → Service Workers → Unregister
2. Clear site data / hard refresh
3. Uninstall old PWA if installed, then Install again

Chrome caches installed-app icons aggressively; reinstall is often required.
