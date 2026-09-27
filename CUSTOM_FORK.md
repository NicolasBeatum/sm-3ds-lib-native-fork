# Custom 3DS engine fork

This repository is a public fork and modified continuation of
[CharlesAverill/sm-3ds-lib](https://github.com/CharlesAverill/sm-3ds-lib), which
is based on [snesrev/sm](https://github.com/snesrev/sm). It exists as the engine
submodule for [`sm-3ds-native`](https://github.com/NicolasBeatum/sm-3ds-native)
and is not an official upstream release.

The custom changes include Old 3DS native frame scheduling, PPU/DSP performance
work, PICA200 integration hooks, optional diagnostics, safe signed fixed-point
collision arithmetic and the overlap-safe BTS room-data fix.

This custom work was developed with extensive OpenAI Codex assistance for
analysis, implementation, debugging and documentation, under human direction
and testing by Nicolás Andrés Hernández Vargas. All original licenses and
upstream attribution remain in effect.
