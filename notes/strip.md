# strip

> Source: TLDR (MIT) — from 'vendor/tldr/'

# strip

> Discard symbols from executables or object files.
> More information: <https://manned.org/strip>.

- Replace the input file with its stripped version:

`strip {{path/to/file}}`

- Strip symbols from a file, saving the output to a specific file:

`strip {{path/to/input_file}} -o {{path/to/output_file}}`

- Strip debug symbols only:

`strip {{[-d|--strip-debug]}} {{path/to/file.o}}`

---
_Imported: 2026-07-31 20:21:47 UTC_
