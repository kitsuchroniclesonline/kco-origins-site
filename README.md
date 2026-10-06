# KCO Origins — site

The GitHub Pages site the game reads at launch, and the home of its public pages.

- **`version.json`** — the update manifest (`VersionCheck` in the game, GDD §9.3). Per platform: `min_version` (below it the game shows a blocking update dialog), `latest_version` (below it a dismissable prompt), `store_url` (where the dialog's button goes). To announce a release: edit the two versions, commit, push — Pages deploys within a minute or two, and every launch after that sees it. The iOS `store_url` stays empty until the app has its App Store id.
- `index.html` — the landing page. The privacy policy and support page the stores require will live here too.

Served at `https://kitsuchroniclesonline.github.io/kco-origins-site/`.
