# pidstat

> Source: TLDR (MIT) — from 'vendor/tldr/'

# pidstat

> Show system resource usage, including CPU, memory, IO etc.
> More information: <https://manned.org/pidstat>.

- Show CPU statistics at a 2 second interval for 10 times:

`pidstat {{2}} {{10}}`

- Show page faults and memory utilization:

`pidstat -r`

- Show input/output usage per process ID:

`pidstat -d`

- Show information on a specific PID:

`pidstat -p {{PID}}`

- Show memory statistics for all processes whose command name include "fox" or "bird":

`pidstat -C "{{fox|bird}}" -r -p ALL`

---
_Imported: 2026-09-27 12:52:30 UTC_
