# <img src="images/icon.svg" width="40" align="top" alt=""> Perspective Measure

Measure real lengths on a flat surface photographed at an angle: a floor, a
wall, a façade, a sheet of paper on a desk.

## [▶ Open Perspective Measure](https://tomaszdzieduszynski.github.io/perspective-measure/)

Version 1.0.0 · runs in any modern browser · nothing to install · your image
never leaves your computer

To use it offline, open the page and save it (Ctrl+S). It is a single file.

## How to use

1. **Load an image.** Drop it on the page, click to browse, or paste it.
2. **Trace a rectangle** that lies in the plane you want to measure: put the
   orange lines along one pair of parallel edges and the blue lines along the
   other, or switch to *Corners* and drag the four corners. If you know its
   real size, enter it. Press **Accept rectangle**.
3. **Calibrate.** Pick *Reference*, draw a line over something of known
   length and type the length (click the line's label on the image to edit
   it). The rectangle size counts as a reference too.
4. **Measure.** Pick *Measure* and draw lines. Copy the results or save an
   annotated PNG.

| Key | Action |
|---|---|
| R / M | Reference / Measure tool |
| H, Space, right or middle drag | Pan |
| F, scroll | Fit, zoom |
| Ctrl+Z / Ctrl+Y | Undo / redo |
| Shift | Snap to 45° while drawing |
| Arrow keys | Nudge the selected point (Shift ×10) |
| Delete | Remove the selected line |

## Good to know

- Only lengths lying in the plane of the traced rectangle are measured
  correctly.
- One reference calibrates one direction: lines that are not parallel to it
  are marked ⚠. A second reference at roughly 90°, or the rectangle size,
  calibrates every direction.
- If a reference and the rectangle size disagree, the value you edited last
  wins and the other is updated to match.
- Accuracy depends on how precisely the edges are traced. Zoom in; the
  magnifier and the arrow keys help.
- Lens effects are not compensated. Barrel or pincushion distortion (common
  with wide-angle and phone cameras) bends straight lines and skews the
  results, most toward the edges of the frame. Use a corrected photo, or keep
  what you measure near the centre of the image.

## License and credits

<img src="images/bzqp_logo.png" width="40" align="middle" alt="bzqp"> Tomasz "bzqp" Dzieduszyński, 2026. With assistance from Claude Opus 5.5.

Licensed under [Creative Commons Attribution-NonCommercial 4.0](LICENSE):
you may share and adapt it for non-commercial purposes, as long as you credit
the author.

What changed in each version: [CHANGELOG.md](CHANGELOG.md).
