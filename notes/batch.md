# batch

> Source: TLDR (MIT) — from 'vendor/tldr/'

# batch

> Execute commands at a later time when the system load levels permit.
> Results will be sent to the user's mail.
> See also: `at`, `atq`, `atrm` `mail`.
> More information: <https://manned.org/batch>.

- Start the `atd` daemon:

`systemctl start atd`

- Execute commands from `stdin` (press `<Ctrl d>` when done):

`batch`

- Execute a command from `stdin`:

`echo "{{./make_db_backup.sh}}" | batch`

---
_Imported: 2026-05-14 09:36:07 UTC_
