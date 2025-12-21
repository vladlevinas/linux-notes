# cockpit-desktop

> Source: TLDR (MIT) — from 'vendor/tldr/'

# cockpit-desktop

> Securely access Cockpit pages in a running session.
> It starts `cockpit-ws` and a web browser in an isolated network space and a `cockpit-bridge` in a running user session.
> More information: <https://cockpit-project.org/guide/latest/cockpit-desktop.1.html>.

- Open a page:

`cockpit-desktop {{url}} {{SSH_host}}`

- Open storage page:

`cockpit-desktop {{/cockpit/@localhost/storage/index.html}}`

---
_Imported: 2025-12-21 13:31:05 UTC_
