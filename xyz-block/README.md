# XYZ Block

A visual reference guide, and a handy 1 inch calibration block.

Each of the three axes reads as its own letter — X, Y and Z — cut through a 1 inch cube, so the block shows you which way is which from any orientation.

> Click the **STL** link to spin the model in GitHub's built-in 3D viewer.

## Model

| | Model | Size | Files |
|---|---|---|---|
| <img src="images/xyz-block.png" width="180"> | **XYZ Block** | 25.4 × 25.5 × 25.4 mm<br>1.00 × 1.00 × 1.00 in | [STL](print/xyz-block.stl) · [3MF](print/xyz-block.3mf)<br>[STEP](cad/xyz-block.step) · [F3D](cad/xyz-block.f3d) |

## Printing

- Mesh is watertight, in millimetres, roughly 31,000 triangles
- Material is about 11.5 cm³

**This version contains two fully sealed internal cavities** — they have no opening to the outside. A slicer will simply enclose them, so if you want anything inside you need to pause the print at the right layer and drop it in before the roof closes over. If you just want a solid block, the cavities are small enough to ignore.

## Source files

- **F3D** — the Fusion model with full feature history
- **STEP** — neutral solid. Note it exports as `BREP_WITH_VOIDS` rather than a plain solid, because of the enclosed cavities; that is valid STEP and loads normally.

Released under [CC0 1.0](../License.txt) — public domain, no attribution required.
