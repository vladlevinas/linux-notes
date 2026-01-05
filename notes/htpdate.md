# htpdate

> Source: TLDR (MIT) — from 'vendor/tldr/'

# htpdate

> Synchronize local date and time via HTTP headers from web servers.
> More information: <https://www.vervest.org/htp/>.

- Synchronize date and time:

`sudo htpdate {{host}}`

- Perform simulation of synchronization, without any action:

`htpdate -q {{host}}`

- Compensate the systematic clock drift:

`sudo htpdate -x {{host}}`

- Set time immediate after the synchronization:

`sudo htpdate -s {{host}}`

---
_Imported: 2026-01-05 13:43:38 UTC_
