# AVR® ASM Navigator

Local VS Code extension that adds practical symbol help for AVR® assembly (`.S/.s`) projects.
Optimized for Microchip® MPLAB® XC8™ (`xc8-cc`) AVR® workflows and device-family packs (DFP).

Source files:
- `vscode-avr-asm-navigator/`

## Quick Start

Build the VSIX:

```sh
cd vscode-avr-asm-navigator
./package-vsix.sh
```

Install the generated VSIX in VS Code:

```sh
code --install-extension ./avr1-local.avr-asm-navigator-<version>.vsix --force
```

Uninstall if needed:

```sh
code --uninstall-extension avr1-local.avr-asm-navigator
```

## Documentation

Full extension documentation is in:
- `vscode-avr-asm-navigator/README.md`

## Trademarks

- Microchip®, MPLAB®, and AVR® are registered trademarks of Microchip® Technology Incorporated (and its subsidiaries) in the U.S. and other countries.
- MPLAB® XC8™ is used in this document as a Microchip® toolchain product name.
- All other trademarks are the property of their respective owners.
- This project is an independent community project and is not affiliated with, endorsed by, or sponsored by Microchip® Technology Incorporated.
