CPALE Recall Deck v6.4

Stable opening splash redo:
- Rebuilt from the stable v6.0 app.
- Uses only the original fiery-eye GIF with a dark adjusted background.
- Removed the extra normal-eye animation.
- The GIF is centered and presented full-screen, not in a small box.
- The splash fades out smoothly into the dashboard.
- The service worker does not require the GIF during installation, so the website will not fail to load because of the splash image.

Files to upload:
- index.html
- manifest.webmanifest
- service-worker.js
- README.txt
- opening-eye-dark.gif

How to update GitHub:
1. Download and extract this ZIP.
2. Upload/replace all five files listed above.
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=64

If Safari still shows the old version, refresh several times or clear website data for the GitHub Pages site.
