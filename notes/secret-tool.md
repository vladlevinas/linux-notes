# secret-tool

> Source: TLDR (MIT) — from 'vendor/tldr/'

# secret-tool

> Store and retrieve passwords, part of the `libsecret` package.
> Communicates with Freedesktop secret service implementations such as `gnome-keyring`.
> More information: <https://gnome.pages.gitlab.gnome.org/libsecret/>.

- Store a secret with an optional label:

`secret-tool store --label={{label}} {{key}} {{value}}`

- Retrieve a secret:

`secret-tool lookup key {{key}}`

- Get more information about a secret:

`secret-tool search key {{key}}`

- Delete a stored secret:

`secret-tool clear key {{key}}`

---
_Imported: 2026-02-15 19:30:11 UTC_
