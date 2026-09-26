# Custom 3DS engine fork

This private repository is a modified continuation of
[CharlesAverill/sm-3ds-lib](https://github.com/CharlesAverill/sm-3ds-lib), which
is based on [snesrev/sm](https://github.com/snesrev/sm). It exists as the engine
submodule for the private `sm-3ds-metroidarch` integration and is not an
official upstream release.

The custom changes include Old 3DS native frame scheduling, PPU/DSP performance
work, PICA200 integration hooks, optional diagnostics, safe signed fixed-point
collision arithmetic and the overlap-safe BTS room-data fix.

This custom work was developed with extensive OpenAI Codex assistance for
analysis, implementation, debugging and documentation, under human direction
and testing by Nicolás Andrés Hernández Vargas. All original licenses and
upstream attribution remain in effect.
