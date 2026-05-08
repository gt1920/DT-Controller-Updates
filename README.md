# DT-Controller-Updates

Auto-update channel for [DT Controller](https://github.com/gt1920) (laser driver host app).

- `latest.json` — manifest the running app polls on startup
- Releases — actual `update.zip` payloads (one per tag)

The app reads `latest.json` from `main`, compares its `version` field to the running `AssemblyVersion`, and offers an in-app upgrade button when newer.
