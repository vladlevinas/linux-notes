# named

> Source: TLDR (MIT) — from 'vendor/tldr/'

# named

> Execute the DNS (Dynamic Name Service) server daemon that converts host names to IP addresses and vice versa.
> More information: <https://manned.org/named>.

- Read the default configuration file `/etc/named.conf`, read any initial data and listen for queries:

`named`

- Read a custom configuration file:

`named -c {{path/to/named.conf}}`

- Use IPv4 or IPv6 only, even if the host machine is capable of utilising other protocols:

`named {{-4|-6}}`

- Listen for queries on a specific port instead of the default port 53:

`named -p {{port}}`

- Run the server in the foreground and do not daemonize:

`named -f`

---
_Imported: 2026-10-14 22:07:30 UTC_
