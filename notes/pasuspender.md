# pasuspender

> Source: TLDR (MIT) — from 'vendor/tldr/'

# pasuspender

> Temporarily suspends `pulseaudio` while another command is running to allow access to alsa.
> More information: <https://manned.org/pasuspender>.

- Suspend PulseAudio while running `jackd`:

`pasuspender -- {{jackd --driver alsa --device hw:0}}`

---
_Imported: 2026-11-21 23:43:31 UTC_
