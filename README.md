# rofi-power

Systemd based power management with [Rofi](https://github.com/DaveDavenport/rofi).

Requires:

- Rofi
- A systemd based Linux distro

Provides:

- Suspend
- Reboot
- Shutdown
- Hibernate

Optional commands:

- Lock: set the `LOCKPRG` ENV variable
- Exit: set the `EXITPRG` ENV variable

## Installation

```bash
pip install --user git+https://github.com/cjbassi/rofi-power
```
