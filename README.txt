GROCERY SHOP BILLING — PWA PACKAGE

Files:
- index.html: billing app
- manifest.webmanifest: installable app metadata
- service-worker.js: offline app shell cache
- icons/: app icons

IMPORTANT:
A Progressive Web App must be served from HTTPS (or localhost) for installation and offline service-worker support.
Opening index.html directly from the phone's Downloads folder will run the billing page, but will not enable PWA installation.

To install:
1. Host the contents of this folder on an HTTPS static hosting service.
2. Open the hosted address in Chrome on Android.
3. Open Chrome's menu (three dots) and choose "Install app" or "Add to Home screen".
4. Confirm the installation.

Data note:
This first version stores product and sales data in browser localStorage on that device. Export sales regularly. It does not sync between devices and is not a tax-compliant GST invoicing/accounting system.
