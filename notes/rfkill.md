# rfkill

> Source: TLDR (MIT) — from 'vendor/tldr/'

# rfkill

> Enable and disable wireless devices.
> More information: <https://manned.org/rfkill>.

- List devices:

`rfkill`

- Filter by columns:

`rfkill {{[-o|--output]}} {{ID,TYPE,DEVICE}}`

- Block devices by type (e.g. bluetooth, wlan):

`rfkill block {{bluetooth}}`

- Unblock devices by type (e.g. bluetooth, wlan):

`rfkill unblock {{wlan}}`

- Output in JSON format:

`rfkill {{[-J|--json]}}`

---
_Imported: 2026-03-28 19:33:39 UTC_
