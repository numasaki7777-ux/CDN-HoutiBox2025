# CDN-HoutiBox2025

HoutiBox runtime update files served through GitHub + jsDelivr.

Base CDN URL:

```text
https://cdn.jsdelivr.net/gh/numasaki7777-ux/CDN-HoutiBox2025@main
```

Configure `GameUpdateBootstrap.versionJsonUrl` in HoutiBox to:

```text
https://cdn.jsdelivr.net/gh/numasaki7777-ux/CDN-HoutiBox2025@main/version.json
```

The diamond upgrade missions are only enabled when both conditions are true:

- `version.json` has `diamond_upgrade_missions` enabled.
- `asset_manifest.json` successfully downloads `missions/diamond_upgrade_missions.json`.
