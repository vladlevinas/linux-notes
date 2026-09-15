# systemd-escape

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemd-escape

> Escape strings for usage in systemd unit names.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-escape.html>.

- Escape the given text:

`systemd-escape {{text}}`

- Reverse the escaping process:

`systemd-escape {{[-u|--unescape]}} {{text}}`

- Treat the given text as a path:

`systemd-escape {{[-p|--path]}} {{text}}`

- Append the given suffix to the escaped text:

`systemd-escape --suffix {{suffix}} {{text}}`

- Use a template and inject the escaped text:

`systemd-escape --template {{template}} {{text}}`

---
_Imported: 2026-09-15 12:32:14 UTC_
