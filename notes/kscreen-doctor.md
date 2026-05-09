# kscreen-doctor

> Source: TLDR (MIT) — from 'vendor/tldr/'

# kscreen-doctor

> Change and manipulate the screen setup.
> More information: <https://invent.kde.org/plasma/libkscreen>.

- Show display output information:

`kscreen-doctor {{[-o|--outputs]}}`

- Set the rotation of a display output with an ID of 1 to the right:

`kscreen-doctor {{output.1.rotation.right}}`

- Set the scale of a display output with an ID of `HDMI-2` to 2 (200%):

`kscreen-doctor {{output.HDMI-2.scale.2}}`

---
_Imported: 2026-05-09 08:43:49 UTC_
