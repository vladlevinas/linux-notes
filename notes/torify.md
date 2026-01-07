# torify

> Source: TLDR (MIT) — from 'vendor/tldr/'

# torify

> Route network traffic through the Tor network.
> Note: This command has been deprecated, and is now a backwards-compatible wrapper of `torsocks`.
> More information: <https://manned.org/torify>.

- Route traffic via Tor:

`torify {{command}}`

- Toggle Tor in shell:

`torify {{on|off}}`

- Spawn a Tor-enabled shell:

`torify --shell`

- Check for a Tor-enabled shell:

`torify show`

- Specify Tor configuration file:

`torify -c {{config-file}} {{command}}`

- Use a specific Tor SOCKS proxy:

`torify -P {{proxy}} {{command}}`

- Redirect output to a file:

`torify {{command}} > {{path/to/output}}`

---
_Imported: 2026-01-07 19:23:58 UTC_
