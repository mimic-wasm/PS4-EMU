# PS4-EMU

PS4-EMU is a PlayStation 4 emulator project for Windows, Linux, and macOS, based on the shadPS4 open-source emulator.

## Project status

This codebase is an early-stage emulator. Compatibility and performance vary by game, and not every title will run correctly.

## Building

Build instructions are available in the `documents` directory:

- `documents/building-windows.md`
- `documents/building-linux.md`
- `documents/building-macos.md`
- `documents/building-docker.md`

## Usage

The uploaded source is the emulator core and does not include a graphical launcher.

For command-line options, consult the executable's `--help` output after building. The original upstream project uses the `shadPS4` executable name; this README rename does not by itself rename compiled targets or internal identifiers.

## Firmware

Some games require PlayStation 4 firmware modules. Firmware files must be obtained from a PlayStation 4 console that you legally own. Do not download firmware files from unofficial sources.

## Controls

The emulator supports Xbox and DualShock controllers. Keyboard mappings and controller bindings can be configured in the emulator settings.

## Original project and attribution

This project is based on [shadPS4](https://github.com/shadps4-emu/shadPS4), created by the shadPS4 Emulator Project and its contributors. The upstream project, its contributors, and their work retain their original attribution.

The original project documentation and contributor information are included in the source tree.

## License

This project is distributed under the GNU General Public License, version 2 or later. See [LICENSE](LICENSE) and the files in [LICENSES](LICENSES) for license details.
