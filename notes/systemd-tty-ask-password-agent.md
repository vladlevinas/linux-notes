# systemd-tty-ask-password-agent

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemd-tty-ask-password-agent

> List or process pending systemd password requests.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-tty-ask-password-agent.html>.

- List all currently pending system password requests:

`systemd-tty-ask-password-agent --list`

- Continuously process password requests:

`systemd-tty-ask-password-agent --watch`

- Process all currently pending system password requests by querying the user on the calling TTY:

`systemd-tty-ask-password-agent --query`

- Forward password requests to wall instead of querying the user on the calling TTY:

`systemd-tty-ask-password-agent --wall`

---
_Imported: 2026-08-18 13:45:09 UTC_
