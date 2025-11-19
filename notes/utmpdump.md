# utmpdump

> Source: TLDR (MIT) — from 'vendor/tldr/'

# utmpdump

> Dump and load btmp, utmp and wtmp accounting files.
> More information: <https://manned.org/utmpdump>.

- Dump the `/var/log/wtmp` file to `stdout` as plain text:

`utmpdump {{/var/log/wtmp}}`

- Load a previously dumped file into `/var/log/wtmp`:

`utmpdump {{[-r|--reverse]}} {{dumpfile}} > {{/var/log/wtmp}}`

---
_Imported: 2025-11-19 19:19:46 UTC_
