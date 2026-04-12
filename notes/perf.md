# perf

> Source: TLDR (MIT) — from 'vendor/tldr/'

# perf

> Framework for Linux performance counter measurements.
> More information: <https://perf.wiki.kernel.org>.

- Display basic performance counter stats for a command:

`perf stat {{gcc hello.c}}`

- Display system-wide real-time performance counter profile:

`sudo perf top`

- Run a command and record its profile into `perf.data`:

`sudo perf record {{command}}`

- Record the profile of an existing process into `perf.data`:

`sudo perf record {{[-p|--pid]}} {{pid}}`

- Read `perf.data` (created by `perf record`) and display the profile:

`sudo perf report`

---
_Imported: 2026-04-12 08:04:10 UTC_
