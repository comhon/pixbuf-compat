# pixbuf-compat

Compatibility (dummy) Debian package to map:

    libgdk-pixbuf2.0-0 -> libgdk-pixbuf-2.0-0

Used for fixing broken dependencies in older packages (for example minecraft.deb)
on Debian 13+.

## Build

```bash
sudo apt install equivs
./build.sh