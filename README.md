# dump-sync — Releases

First-party Obsidian plugin for [dump](https://dump.apps.bcbas.com): syncs a vault with a
dump server over HTTPS — **no git on the device**, conflicts never lose bytes.
Built from the dump monorepo (`apps/obsidian`).

## Install (BRAT — desktop & mobile)

1. Obsidian → Community plugins → install & enable **BRAT**
2. BRAT settings → **Add beta plugin** → `bennniii/obsidian-dump-sync-releases`
3. Enable **dump sync** under Community plugins
4. Plugin settings: server URL + `dump_…` API key (create it in the dump web app,
   scopes read+write) → *Verbindung testen* → *Jetzt syncen*

BRAT installs from the **GitHub Releases** of this repo (assets: `main.js` +
`manifest.json`, release tag == manifest version). The copies at the repo root mirror
the latest release for manual installs: copy both files into
`<vault>/.obsidian/plugins/dump-sync/` and reload Obsidian.
