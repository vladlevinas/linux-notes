# add-apt-repository

> Source: TLDR (MIT) — from 'vendor/tldr/'

# add-apt-repository

> Manage `apt` repository definitions.
> More information: <https://manned.org/add-apt-repository>.

- Add a new `apt` repository:

`add-apt-repository {{repository_spec}}`

- Remove an `apt` repository:

`add-apt-repository {{[-r|--remove]}} {{repository_spec}}`

- Update the package cache after adding a repository:

`add-apt-repository --update {{repository_spec}}`

- Allow source packages to be downloaded from the repository:

`add-apt-repository {{[-s|--enable-source]}} {{repository_spec}}`

---
_Imported: 2026-04-29 09:12:08 UTC_
