# systemd-sysext

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemd-sysext

> Activate or deactivate system extension images.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-sysext.html>.

- List installed extension images:

`systemd-sysext list`

- Merge system extension images into `/usr/` and `/opt/`:

`systemd-sysext merge`

- Check the current merge status:

`systemd-sysext status`

- Unmerge all currently installed system extension images from `/usr/` and `/opt/`:

`systemd-sysext unmerge`

- Refresh system extension images (a combination of `unmerge` and `merge`):

`systemd-sysext refresh`

---
_Imported: 2026-04-16 08:47:04 UTC_
