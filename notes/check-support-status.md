# check-support-status

> Source: TLDR (MIT) — from 'vendor/tldr/'

# check-support-status

> Identify installed Debian packages for which support has had to be limited or prematurely ended.
> More information: <https://manned.org/check-support-status>.

- Display packages whose support is limited, has already ended or will end earlier than the distribution's end of life:

`check-support-status`

- Display only packages whose support has ended:

`check-support-status --type {{ended}}`

- Skip printing a headline:

`check-support-status --no-heading`

---
_Imported: 2026-07-04 14:40:20 UTC_
