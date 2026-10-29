# lazar-connect

Two static pages for Lazar Autopilot, served by GitHub Pages at
https://malonescousin.github.io/lazar-connect/.

eBay and AliExpress only send you back to an https address after you approve the app. These pages
pass that straight on, in the same browser, to the app running on your PC at http://127.0.0.1:8787:

- `ebay.html` → `/oauth/ebay/callback` (eBay RuName → "Your auth accepted URL")
- `aliexpress.html` → `/oauth/aliexpress/callback` (AliExpress app → "Callback URL")

Nothing is stored or sent anywhere else. No keys, code or data belong in this repository.
