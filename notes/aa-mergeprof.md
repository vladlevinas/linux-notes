# aa-mergeprof

> Source: TLDR (MIT) — from 'vendor/tldr/'

# aa-mergeprof

> Merge AppArmor security profile files into the profile directory.
> More information: <https://gitlab.com/apparmor/apparmor/-/wikis/manpage_aa-mergeprof.8>.

- Merge one or more profile files into the default profile directory:

`sudo aa-mergeprof {{file1 file2 ...}}`

- Merge profile files into a specific directory:

`sudo aa-mergeprof {{[-d|--dir]}} /{{path/to/profiles}} {{file1 file2 ...}}`

- Display help:

`aa-mergeprof {{[-h|--help]}}`

---
_Imported: 2026-03-26 08:03:48 UTC_
