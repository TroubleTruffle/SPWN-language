# SPWN-language

A language for Geometry Dash triggers. An easy way to create levels using code.

# Installing - How To Install

## Windows
1. Download the .msi file from the [latest release](https://github.com/Spu7Nix/SPWN-language/releases).
2. Open the .msi file and follow the install wizard.

## MacOS
1. Download the .pkg file from the [latest release](https://github.com/Spu7Nix/SPWN-language/releases).
2. Open the .pkg file and follow the install wizard.

## Linux
Coming soon.

## Compiling from source
1. Download source code from this repository.
2. Install rust if you haven't already.
3. Open `spwn-lang` folder in the terminal.
4. Run `cargo build`.
5. Compiled binary is placed in `target/debug`.
> note that with a compiled build, libraries may not be in the same directory as the executable making you unable to use the standard library. When building with SPWN you must include the directory that has `libraries/` or move `libraries/` to the executable directory.

# Documentation

The documentation for the SPWN language is located at https://spu7nix.net/spwn/#/. You can also contribute here: https://github.com/Spu7Nix/spwn_docs

# Todo before release:

- [x] Finish mutable variables
- [x] Type annotations for function arguments, variable definitions etc.
- [x] `as` operator for automatically changing type
- [ ] finish documentation
- [x] break/continue statement
- [x] operation order
- [x] escaped characters in string
- [x] fix post-compile optimizations

# Todo at some point

- [x] implement live editor features for windows
- [ ] make it work on linux
- [x] nested comments
- [x] get and edit obj and trigger properties

# Enjoy SPWN!
