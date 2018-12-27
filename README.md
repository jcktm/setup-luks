setup-luks
----------

This script sets up a LUKS encrypted device, installs alpine, and configures
the bootloader. If this system is not yet configured, run setup-alpine and
skip the disk selection.

    ash <(curl https://raw.githubusercontent.com/jcktm/setup-luks/master/setup-luks)
