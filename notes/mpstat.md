# mpstat

> Source: TLDR (MIT) — from 'vendor/tldr/'

# mpstat

> Report CPU statistics.
> More information: <https://manned.org/mpstat>.

- Display CPU statistics every 2 seconds:

`mpstat {{2}}`

- Display 5 reports, one by one, at 2 second intervals:

`mpstat {{2}} {{5}}`

- Display 5 reports, one by one, from a given processor, at 2 second intervals:

`mpstat -P {{0}} {{2}} {{5}}`

---
_Imported: 2026-03-04 19:39:55 UTC_
