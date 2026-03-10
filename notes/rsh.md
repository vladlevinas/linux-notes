# rsh

> Source: TLDR (MIT) — from 'vendor/tldr/'

# rsh

> Execute commands on a remote host.
> More information: <https://www.gnu.org/software/inetutils/manual/inetutils.html#rsh-invocation>.

- Execute a command on a remote host:

`rsh {{remote_host}} {{ls -l}}`

- Execute a command on a remote host with a specific username:

`rsh {{remote_host}} {{[-l|--user]}} {{username}} {{ls -l}}`

- Redirect `stdin` to `/dev/null` when executing a command on a remote host:

`rsh {{remote_host}} --no-err {{ls -l}}`

---
_Imported: 2026-03-10 07:43:35 UTC_
