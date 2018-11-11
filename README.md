# rofi-power

Systemd based power management with [Rofi](https://github.com/DaveDavenport/rofi).

Requires:

- rofi
- a systemd based Linux distro

Provides:

- Suspend
- Reboot
- Poweroff
- Hibernate

Add a Lock command to the options by settings the `LOCKPRG` ENV variable.

## Installation

```bash
pip install --user git+https://github.com/cjbassi/rofi-power
```
