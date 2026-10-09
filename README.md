# rDownloader for Scoop

The Scoop bucket of [rDownloader](https://rdownloader.net), a local-first download manager with a
web interface, for Windows x86-64.

```powershell
scoop bucket add rdownloader https://github.com/degoya/scoop-rdownloader
scoop install rdownloader
start-rdownloader
```

Then open <http://127.0.0.1:8710> and follow the setup wizard. The database, plugins and default
download folder live in Scoop's persist folder, and `scoop update rdownloader` keeps them; stop
the service with `stop-rdownloader` before updating.

Current version: 1.22.0. The manifest is written by the release workflow of
[degoya/rDownloader](https://github.com/degoya/rDownloader) with every release — issues and changes go there,
not here. The handbook's installation page:
<https://github.com/degoya/rDownloader/wiki/installation>.
