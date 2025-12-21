# logread

> Source: TLDR (MIT) — from 'vendor/tldr/'

# logread

> Read the `logd` ring buffer log.
> More information: <https://openwrt.org/docs/guide-user/base-system/log.essentials>.

- Print the log:

`logread`

- Print `n` messages:

`logread -l {{n}}`

- Filter messages by (Keyword/`regex`):

`logread -e {{pattern}}`

- Print log messages as they happen:

`logread -f`

- Display help:

`logread -h`

---
_Imported: 2025-12-21 07:23:23 UTC_
