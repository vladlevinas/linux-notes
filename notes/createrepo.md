# createrepo

> Source: TLDR (MIT) — from 'vendor/tldr/'

# createrepo

> Initialize an RPM repository in a directory, including all XML and SQLite files.
> More information: <https://manned.org/createrepo>.

- Initialize a basic repository in a directory:

`createrepo {{path/to/directory}}`

- Initialize a repository, exclude test RPMs and display verbose logs:

`createrepo {{[-v|--verbose]}} {{[-x|--excludes]}} {{test_*.rpm}} {{path/to/directory}}`

- Initialize a repository, using SHA1 as the checksum algorithm, and ignoring symbolic links:

`createrepo {{[-S|--skip-symlinks]}} {{[-s|--checksum]}} {{sha1}} {{path/to/directory}}`

---
_Imported: 2025-11-26 19:19:03 UTC_
