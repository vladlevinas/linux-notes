# flatpak-mask

> Source: TLDR (MIT) — from 'vendor/tldr/'

# flatpak mask

> Mask out updates and automatic installation.
> More information: <https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak-mask>.

- Ignore updates for a specific flatpak:

`flatpak mask {{com.example.app}}`

- Undo ignore updates:

`flatpak mask --remove {{com.example.app}}`

- List all currently masked patterns:

`flatpak mask {{--system|--user}}`

---
_Imported: 2026-05-02 14:10:59 UTC_
