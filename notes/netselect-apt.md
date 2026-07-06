# netselect-apt

> Source: TLDR (MIT) — from 'vendor/tldr/'

# netselect-apt

> Create a `sources.list` file for a Debian mirror with the lowest latency.
> More information: <https://manned.org/netselect-apt>.

- Create `sources.list` using the lowest latency server:

`sudo netselect-apt`

- Specify Debian branch, stable is used by default:

`sudo netselect-apt {{testing}}`

- Include non-free section:

`sudo netselect-apt {{[-n|--non-free]}}`

- Specify a country for the mirror list lookup:

`sudo netselect-apt {{[-c|--country]}} {{India}}`

---
_Imported: 2026-07-06 16:23:52 UTC_
