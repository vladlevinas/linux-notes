# isosize

> Source: TLDR (MIT) — from 'vendor/tldr/'

# isosize

> Display the size of an ISO file.
> More information: <https://manned.org/isosize>.

- Display the size of an ISO file:

`isosize {{path/to/file.iso}}`

- Display the block count and block size of an ISO file:

`isosize {{[-x|--sectors]}} {{path/to/file.iso}}`

- Display the size of an ISO file divided by a given number (only usable when --sectors is not given):

`isosize {{[-d|--divisor]}} {{number}} {{path/to/file.iso}}`

---
_Imported: 2026-07-24 09:22:53 UTC_
