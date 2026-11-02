# meum widgets

The widget library of meum, Max Studanski's native macOS workspace for terminal agent sessions.

meum reads `catalog.json` from this repo (Settings ▸ Widgets ▸ Widget Library, or `meum widget catalog`). Each widget
is a zipped `.meumwidget` folder attached to a release here; the catalog pins the zip's sha256, and meum refuses a
download that doesn't match. After installing, meum pins the widget's library and checks it before every load.

Widgets are published with `scripts/release-widget.sh … --publish` from the meum repo and signed with the
Developer ID of Max Studanski (Team XHXWK3RG86).
