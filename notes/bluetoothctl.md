# bluetoothctl

> Source: TLDR (MIT) — from 'vendor/tldr/'

# bluetoothctl

> Manage Bluetooth devices.
> See also: `bluetui`.
> More information: <https://manned.org/bluetoothctl>.

- Enter the `bluetoothctl` shell:

`bluetoothctl`

- List all known devices:

`bluetoothctl devices`

- Power the Bluetooth controller on or off:

`bluetoothctl power {{on|off}}`

- Pair with a device:

`bluetoothctl pair {{mac_address}}`

- Remove a device:

`bluetoothctl remove {{mac_address}}`

- Connect to a paired device:

`bluetoothctl connect {{mac_address}}`

- Disconnect from a paired device:

`bluetoothctl disconnect {{mac_address}}`

- Display help:

`bluetoothctl help`

---
_Imported: 2026-05-07 15:28:33 UTC_
