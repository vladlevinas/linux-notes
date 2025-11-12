# flatpak-update

> Source: TLDR (MIT) — from 'vendor/tldr/'

# flatpak update

> Update flatpak applications and runtimes.
> More information: <https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak-update>.

- Update all installed applications and runtimes (use `-y` to confirm all prompts automatically):

`flatpak update`

- Update only a specific app:

`flatpak update {{com.example.app}}`

- Update/Downgrade to a specific commit (also see flatpak remote-info and flatpak mask):

`flatpak update --commit {{COMMIT}} {{com.example.app}}`

---
_Imported: 2025-11-12 19:20:24 UTC_
