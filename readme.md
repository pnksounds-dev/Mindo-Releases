# PNK // MINDO — Releases

Binaries-only distribution for **Mindo** desktop (Windows, x64). No source
code lives here — published releases and update metadata only.

## Download

Get the latest installer from [**Releases**](../../releases/latest):

- `PNK--MINDO-Setup-<version>.exe` — NSIS installer (per-user, choose your
  install folder)
- `latest.yml` / `.blockmap` — update metadata consumed by the app, no
  manual download needed

## Auto-updates

Installed builds check this repo's releases automatically — Settings →
About → **Desktop updates** runs a check, downloads, and installs on
restart. `latest.yml` in each release is what the app reads.

## Unsigned build notice

Current builds are **unsigned**. Mindo is safe and tested — Windows
SmartScreen may show "Windows protected your PC" on install or update
(More info → Run anyway). Signed builds follow once a certificate is
provisioned.

## Report a bug

- [Open an issue](../../issues/new) on this repo
- https://pnksounds.dev
