# cam

> Source: TLDR (MIT) — from 'vendor/tldr/'

# cam

> Frontend tool for `libcamera`.
> More information: <https://libcamera.org/docs.html>.

- List available cameras:

`cam {{[-l|--list]}}`

- List controls of a camera:

`cam {{[-c|--camera]}} {{camera_index}} --list-controls`

- Write frames to a folder:

`cam {{[-c|--camera]}} {{camera_index}} {{[-C|--capture=]}}{{frames_to_capture}} {{[-F|--file]}}`

- Display camera feed in a window:

`cam {{[-c|--camera]}} {{camera_index}} {{[-C|--capture]}} {{[-S|--sdl]}}`

---
_Imported: 2026-08-18 07:40:39 UTC_
