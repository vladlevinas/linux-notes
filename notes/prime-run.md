# prime-run

> Source: TLDR (MIT) — from 'vendor/tldr/'

# prime-run

> Run a program using an alternative Nvidia graphics card.
> More information: <https://wiki.archlinux.org/title/PRIME#PRIME_render_offload>.

- Run a program using a dedicated Nvidia GPU:

`prime-run {{command}}`

- Validate whether the Nvidia card is being used:

`prime-run glxinfo | grep "OpenGL renderer"`

---
_Imported: 2026-11-19 01:00:31 UTC_
