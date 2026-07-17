# unshadow

> Source: TLDR (MIT) — from 'vendor/tldr/'

# unshadow

> Utility provided by the John the Ripper project to obtain the traditional Unix password file if the system uses shadow passwords.
> More information: <https://www.openwall.com/john/doc/>.

- Combine the `/etc/shadow` and `/etc/passwd` of the current system:

`sudo unshadow /etc/passwd /etc/shadow`

- Combine two arbitrary shadow and password files:

`sudo unshadow {{path/to/passwd}} {{path/to/shadow}}`

---
_Imported: 2026-07-17 14:45:44 UTC_
