# dos2unix

> Source: TLDR (MIT) — from 'vendor/tldr/'

# dos2unix

> Change DOS-style line endings to Unix-style.
> Replaces CRLF with LF.
> See also: `unix2dos`, `unix2mac`, `mac2unix`.
> More information: <https://manned.org/dos2unix>.

- Change the line endings of a file:

`dos2unix {{path/to/file}}`

- Create a copy with Unix-style line endings:

`dos2unix {{[-n|--newfile]}} {{path/to/file}} {{path/to/new_file}}`

- Display file information:

`dos2unix {{[-i|--info]}} {{path/to/file}}`

- Keep/add/remove Byte Order Mark:

`dos2unix --{{keep-bom|add-bom|remove-bom}} {{path/to/file}}`

---
_Imported: 2026-11-18 16:17:27 UTC_
