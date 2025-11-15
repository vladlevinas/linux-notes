# cockpit-ws

> Source: TLDR (MIT) — from 'vendor/tldr/'

# cockpit-ws

> Communicate between the browser application and various configuration tools and services like `cockpit-bridge`.
> More information: <https://cockpit-project.org/guide/latest/cockpit-ws.8.html>.

- Start with authentication via SSH at `127.0.0.1` with port `22` enabled:

`cockpit-ws --local-ssh`

- Start an HTTP server on a specific port:

`cockpit-ws --port {{port}}`

- Start and bind to a specific IP address (defaults to `0.0.0.0`):

`cockpit-ws --address {{ip_address}}`

- Start without TLS:

`cockpit-ws --no-tls`

- Display help:

`cockpit-ws --help`

---
_Imported: 2025-11-15 19:16:32 UTC_
