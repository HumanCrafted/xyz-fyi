# XYZ FYI

An archive of CAD files, STLs, and other useful downloads.

Everything here is released under [CC0 1.0](License.txt) — public domain, no attribution required. Print it, remix it, sell it, whatever you like.

## Projects

| | Project | Description |
|---|---|---|
| <img src="packout-inserts/images/wide-bin-corner-ul-lr.png" width="140"> | [**Packout Inserts**](packout-inserts/) | Inserts that subdivide the bins of a Milwaukee Packout tray organizer |
| | [Alpha Blocks](alpha-blocks/) | A set of 1 inch alphabet letter blocks |
| | [IKEA Trofast LEGO Bins](trofast-lego-bins/) | Bins and dividers to organize LEGO in IKEA Trofast storage boxes |
| | [IKEA Trofast Storage Box](trofast-storage-box/) | Half-height and short storage boxes for IKEA Trofast frames |
| | [XYZ Block](xyz-block/) | Calibration and reference block |

## Layout

Each project folder follows the same shape:

```
project-name/
├── README.md     model table with sizes, fit notes and download links
├── images/       thumbnails (orthographic isometric, transparent background)
├── print/        .stl and .3mf  — ready to slice
└── cad/          .step and .f3d — editable source
```

Filenames are lowercase kebab-case, and every format for a given model shares one basename, so `cad/thing.step` and `print/thing.stl` are always the same part.

## Viewing models

GitHub renders `.stl` files with an interactive viewer — click any STL in this repo and you can drag to spin it, right-drag to pan, and scroll to zoom. No download needed to see what something is.

STL files must be under 10 MB for the viewer to work, so meshes here are exported at a resolution that stays well inside that while remaining accurate to within a few thousandths of a percent by volume.

## Formats

| Format | What it is | Use it for |
|---|---|---|
| **STL** | Binary triangle mesh, millimetres | Slicing, quick preview in GitHub |
| **3MF** | Modern mesh container, units declared in-file | Slicing — preferred where supported |
| **STEP** | Neutral solid, no history | Editing in any CAD package |
| **F3D** | Fusion archive with full feature history | Editing parametrically in Fusion |

> Projects other than Packout Inserts predate this layout and are still being migrated.
