# pvck

> Source: TLDR (MIT) — from 'vendor/tldr/'

# pvck

> Check and repair LVM metadata on physical volumes.
> More information: <https://manned.org/pvck>.

- Print LVM on-disk headers and structures (label, PV header, MDA header, metadata area):

`pvck {{/dev/sdXN}} --dump headers`

- Print the current VG metadata text:

`pvck {{/dev/sdXN}} --dump metadata`

- List all metadata versions found in the metadata area:

`pvck {{/dev/sdXN}} --dump metadata_all`

- Search common locations for metadata when headers may be damaged, and save it to a file:

`pvck {{/dev/sdXN}} --dump metadata_search {{[-f|--file]}} {{path/to/metadata.txt}}`

- Select the second metadata area (mda2) when printing metadata:

`pvck {{/dev/sdXN}} --dump metadata --settings "mda_num=2"`

- Repair headers and metadata using a metadata input file (use with care):

`pvck {{/dev/sdXN}} --repair {{[-f|--file]}} {{path/to/metadata_file}}`

- Repair only the PV header and label header:

`pvck {{/dev/sdXN}} --repairtype pv_header`

---
_Imported: 2026-11-09 17:17:21 UTC_
