# StashApp legal pages

The published Privacy Policy and Terms of Service for **StashApp**.

| Page | URL |
|---|---|
| Privacy Policy | https://sharonmbae.github.io/stashapp-legal/ |
| Terms of Service | https://sharonmbae.github.io/stashapp-legal/terms.html |

## These files are generated — don't edit them here

Both HTML files are built from markdown in the (private) StashApp app repo,
by `scripts/build-legal-site.py`. Editing them here means the next build
overwrites your change and the markdown stops being the source of truth.

To publish an update: edit the markdown in the app repo, run the build
script, copy `docs/site/*.html` over the files here, and push.

The repo name is load-bearing. These URLs are compiled into the app in
`src/constants/legal.ts`, and Google Play holds the privacy policy URL on
the store listing. Renaming this repo breaks both.
