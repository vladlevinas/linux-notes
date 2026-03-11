# pdfattach

> Source: TLDR (MIT) — from 'vendor/tldr/'

# pdfattach

> Add a new attachment (embedded file) to an existing PDF file.
> See also: `pdfdetach`, `pdfimages`, `pdfinfo`.
> More information: <https://manned.org/pdfattach>.

- Add a new attachment to an existing PDF file:

`pdfattach {{path/to/input.pdf}} {{path/to/file_to_attach}} {{path/to/output.pdf}}`

- Replace attachment with same name if it exists:

`pdfattach -replace {{path/to/input.pdf}} {{path/to/file_to_attach}} {{path/to/output.pdf}}`

- Display help:

`pdfattach {{[-h|--help]}}`

- Display version:

`pdfattach -v`

---
_Imported: 2026-03-11 19:42:04 UTC_
