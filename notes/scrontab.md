# scrontab

> Source: TLDR (MIT) — from 'vendor/tldr/'

# scrontab

> Manage Slurm crontab files.
> More information: <https://slurm.schedmd.com/scrontab.html>.

- Install a new crontab from the specified file:

`scrontab {{path/to/file}}`

- [e]dit the crontab of the current user:

`scrontab -e`

- [e]dit the crontab of the specified user:

`scrontab --user={{user_id}} -e`

- [r]emove the current crontab:

`scrontab -r`

- Print the crontab of the current user to `stdout`:

`scrontab -l`

---
_Imported: 2026-05-29 16:45:35 UTC_
