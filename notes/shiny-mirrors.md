# shiny-mirrors

> Source: TLDR (MIT) — from 'vendor/tldr/'

# shiny-mirrors

> Generate a `pacman` mirror list for Manjaro Linux.
> Every run of shiny-mirrors requires you to synchronize your database and update your system using `sudo pacman -Syyu`.
> More information: <https://gitlab.com/Arisa_Snowbell/shiny-mirrors/-/blob/domina/shiny-mirrors/man/shiny-mirrors.md>.

- Get the status of the current mirrors:

`shiny-mirrors status`

- Generate a mirror list using the default behavior:

`sudo shiny-mirrors refresh`

- Display the current configuration file:

`shiny-mirrors config show`

- Switch to a different branch interactively:

`sudo shiny-mirrors config --branch`

---
_Imported: 2026-05-19 16:24:22 UTC_
