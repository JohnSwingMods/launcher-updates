# launcher-updates

Update notices for the launcher. The app reads `ultima.json` at startup to know if a new version is out.

`ultima.json` fields: `versione` (latest version), `data`, `note` (what's new, per language: `it`, `en`, `de`, `fr`, `es`),
optional `pagina` (download page), optional `exe` + `sha256` + `byte` (direct download, GitHub only),
optional `trasloco` (new address of this file, if it ever moves).
`sostenitori` (optional): list of Swing++ supporter names shown in the app's credits.
