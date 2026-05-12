# einfo

> Source: TLDR (MIT) — from 'vendor/tldr/'

# einfo

> Provides the number of records indexed in each database field, the last update date of the database, and the available links from the database to other Entrez databases.
> More information: <https://www.ncbi.nlm.nih.gov/books/NBK179288/>.

- Print all database names:

`einfo -dbs`

- Print all information of the protein database in XML format:

`einfo -db {{protein}}`

- Print all fields of the nuccore database:

`einfo -db {{nuccore}} -fields`

- Print all links of the protein database:

`einfo -db {{protein}} -links`

---
_Imported: 2026-05-12 15:40:59 UTC_
