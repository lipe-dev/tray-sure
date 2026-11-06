# tray-sure

Parametric, modular makeup / desk organizer for 3D printing, written in OpenSCAD.

- `bin.scad`: a bin N cups wide. Set the `walls` / `floors` arrays to choose, per slot, a walled pocket and a solid floor or a through hole. The wall profile is a trapezoid with configurable corner radii.
- `cup.scad`: a removable insert with configurable height and divider grid.
- `modules/`: shared shapes (`stadium.scad`, `trapezoid.scad`), included by relative path.

No external libraries. Open a file in OpenSCAD, edit the `CONFIGURE HERE` block, then render and export.

Older designs (decor walls, `tray-*.scad`, previews) are still in the git history.

## Exports

`exports/` holds final STL/3MF files. `exports/wip/` is local only (ignored by git).

## History

Extracted in 2026-11 from `makeup-organizer/` in [lipe-dev/personal-3d-files](https://github.com/lipe-dev/personal-3d-files), with its history preserved.

## License

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) (see `LICENSE`). You may share and adapt it for non-commercial use, with attribution and under the same license.
