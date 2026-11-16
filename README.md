# Geomino — website

Static site (plain HTML + one CSS file, no build step, no web font), hosted on GitHub Pages.
Colours = the app's tokens (`Geomino/Views/Components/Theme.swift`, `SplashView.swift`).

| Page | French | English |
|---|---|---|
| Home (App Store "Marketing URL") | `/` | `/en/` |
| Privacy policy (App Store "Privacy Policy URL") | `/privacy/` | `/en/privacy/` |
| Support + legal notice (App Store "Support URL") | `/support/` | `/en/support/` |

Live: https://sofienazzouz.github.io/geomino-website/

## Before / after the App Store release

Search for `TODO` and replace the "Bientôt sur l'App Store" / "Coming soon" buttons with the App Store link
`https://apps.apple.com/app/id6835195947`.

## Keep it in sync with the app

If the app changes what it stores, a permission, the price (2,99 €) or what is free, update the privacy and support
pages (FR + EN) and the date at the top of the privacy policy. Screenshots in `assets/screens/` come from
`design/store-screenshots/` in the app repo.

## Preview locally

Run `python3 -m http.server` in this folder and open http://localhost:8000.
