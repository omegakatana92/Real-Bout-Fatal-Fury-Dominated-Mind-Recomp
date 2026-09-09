$Project = "C:\Users\omega\Documents\tools\psxrecomp-cli-windows-x86_64\Fatal-Fury-Dominated-Mind-Recomp"
Set-Location -LiteralPath $Project

@'
# Real Bout Garou Densetsu Special: Dominated Mind Recomp

A native PlayStation recompilation of **Real Bout Garou Densetsu Special: Dominated Mind** for the original PlayStation.

This project is built with [mstan's PSXRecomp](https://github.com/mstan/psxrecomp).

## Status

The Windows recompilation currently builds and launches successfully.

- Original title: Real Bout Garou Densetsu Special: Dominated Mind
- English title: Fatal Fury: Dominated Mind
- Region: Japan
- Disc serial: `SLPM-860.85`
- Platform: PlayStation
- Players: 2
- Renderer: OpenGL
- Controller mode: Digital
- Recompiled functions: 2,721
- Initial JAL seeds: 1,357

## Requirements

- Windows 10 or newer
- Git
- CMake
- Ninja
- Python 3
- Clang or MinGW-compatible toolchain
- Your own legally obtained PlayStation game dump

## Game Setup

Place your legally obtained game files in the local `disc` directory.

```text
disc/
├── game.cue
└── the BIN file referenced by game.cue
