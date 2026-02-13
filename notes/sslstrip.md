# sslstrip

> Source: TLDR (MIT) — from 'vendor/tldr/'

# sslstrip

> Perform Moxie Marlinspike's Secure Sockets Layer (SSL) stripping attacks.
> Perform an ARP spoofing attack in conjunction.
> More information: <https://www.kali.org/tools/sslstrip/>.

- Log only HTTPS POST traffic on port 10000 by default:

`sslstrip`

- Log only HTTPS POST traffic on port 8080:

`sslstrip --listen={{8080}}`

- Log all SSL traffic to and from the server on port 8080:

`sslstrip --ssl --listen={{8080}}`

- Log all SSL and HTTP traffic to and from the server on port 8080:

`sslstrip --listen={{8080}} --all`

- Specify the file path to store the logs:

`sslstrip --listen={{8080}} --write={{path/to/file}}`

- Display help:

`sslstrip --help`

---
_Imported: 2026-02-13 07:52:35 UTC_
