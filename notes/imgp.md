# imgp

> Source: TLDR (MIT) — from 'vendor/tldr/'

# imgp

> Resize and rotate JPEG and PNG images.
> More information: <https://github.com/jarun/imgp>.

- Convert single images and/or whole directories containing valid image formats:

`imgp {{[-x|--res]}} {{1366x1000}} {{path/to/directory}} {{path/to/file}}`

- Scale an image by 75% and overwrite the source image to a target resolution:

`imgp {{[-x|--res]}} {{75}} z-w {{path/to/file}}`

- Rotate an image clockwise by 90 degrees:

`imgp {{[-o|--rotate]}} {{90}} {{path/to/file}}`

---
_Imported: 2026-02-27 14:01:16 UTC_
