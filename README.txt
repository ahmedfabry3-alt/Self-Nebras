Self-Nebras PWA starter

IMPORTANT
- This is a free installable web-app shell, not a native App Store / Google Play app.
- Replace icons/icon-192.png and icons/icon-512.png with the approved Al Nebras logo in square PNG format.
- Host the files on an HTTPS static host (e.g. GitHub Pages). Do not publish employee passwords or session IDs.
- The launcher opens the ONYXESS URL in a separate browser tab because the destination currently uses plain HTTP.
- For a more seamless app-like experience, put the ONYXESS endpoint behind HTTPS and then test on company devices.
- The target link intentionally omits the session number from the provided URL:
  http://142.154.98.60:8182/apex/f?p=ONYXESS:1
  Confirm with the ONYX/Oracle APEX administrator that this stable URL starts a new login session as expected.

Files:
- index.html: launcher page
- manifest.json: app name and install icon configuration
- sw.js: caches the launcher shell only
- icons/: placeholder app icons; replace with company logo
