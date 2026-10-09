# arpspoof

> Source: TLDR (MIT) — from 'vendor/tldr/'

# arpspoof

> Forge ARP replies to intercept packets.
> More information: <https://manned.org/arpspoof>.

- Poison all hosts to intercept packets on [i]nterface for the host:

`sudo arpspoof -i {{wlan0}} {{host_ip}}`

- Poison [t]arget to intercept packets on [i]nterface for the host:

`sudo arpspoof -i {{wlan0}} -t {{target_ip}} {{host_ip}}`

- Poison both [t]arget and host to intercept packets on [i]nterface for the host:

`sudo arpspoof -i {{wlan0}} -r -t {{target_ip}} {{host_ip}}`

---
_Imported: 2026-10-09 23:06:08 UTC_
