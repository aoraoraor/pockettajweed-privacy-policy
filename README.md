# Pocket Tajweed: privacy policy

The public privacy policy of **Pocket Tajweed** («التجويد في الجيب», `com.ora.tajweed`), the free app for learning
tajweed, in Arabic and English, served by GitHub Pages:

**https://aoraoraor.github.io/pockettajweed-privacy-policy/**

- `index.html` is the whole site: one self-contained page (no external scripts, fonts, cookies or analytics). Arabic and
  English are on the same page; `?lang=ar` or `?lang=en` picks the language, otherwise the browser language does.
- The app opens this URL from Help and privacy → Privacy policy (`app.privacy_url` of `projects/tajweed/project.json`
  in `aoraoraor/app_engine`), adding `?lang=`. Use the same URL in Google Play Console → App content → Privacy policy.
- What it covers: data on the device, Firebase usage statistics, a completely free app (no subscriptions or purchases),
  recitations streamed from EveryAyah at play time (not stored), the daily reminder, backup, children's privacy.

## Hosting

GitHub → this repo → **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** → Save.
The site is live a minute later.

## Updating

Edit both languages in `index.html` and change the "Last updated" date in both. Keep the policy in step with the app's
real data practices and with the Play Console Data safety form.

© 2026 Ahmed Orabi. All rights reserved.
