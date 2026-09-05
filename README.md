# HTML Tools Suite

A collection of high-performance, client-side, zero-install web tools designed for maker, hardware, and document workflows.

**Web app:** [arkadiraf.github.io/HTML_Tools](https://arkadiraf.github.io/HTML_Tools/)

## Tools Overview

### 1. [DXFPreview.html](DXFPreview.html)
**Simple CAD Inspector & Previewer**
- **Drop & View**: Drag and drop a `.dxf` or `.svg` file for instant client-side rendering.
- **Focused CAD Viewport**: Pan, mouse-wheel zoom, fit-to-drawing, cursor coordinates, drawing dimensions, and entity counts.
- **Geometry Support**: Lines, arcs, circles, ellipses, bulged polylines, splines, faces, points, and transformed block inserts.

### 2. [Gerber2Stencil.html](Gerber2Stencil.html)
**SMD Laser Stencil Generator**
- Convert RS-274X Gerber solder paste layers (`.gtp`, `.gbp`, `.zip`) into previewable, laser-cuttable DXF or SVG files.
- Apply a millimetre aperture offset before export, with the compensated holes overlaid on the original preview.

### 3. [Cropper.html](Cropper.html)
**Pot Gallery Thumbnail Helper**
- Image cropping, aspect ratio adjustments, and gallery thumbnail optimization.

### 4. [PDFMerger.html](PDFMerger.html)
**Local PDF Merger & Arranger**
- Client-side PDF page rearrangement and document merging powered by `pdf-lib`.

### 5. [PCBMotorDesigner.html](PCBMotorDesigner.html)
**2-Layer Axial-Flux BLDC Motor Coil & Torque Designer**
- Interactive 2-layer planar coil generator with continuous trapezoidal spirals, centered layer vias, and rotor magnet overlays.
- Real-time electromechanical simulator calculating stall torque, $K_t$, $K_v$, no-load speed, phase resistance, and thermal dissipation.
- JSON parameter save/load and multi-layer CAD DXF export for PCB and mechanical fabrication.

### 6. [PCBTraceCalc.html](PCBTraceCalc.html)
**PCB Trace Resistance & Thermal Calculator (One-Pager)**
- IPC-2152 and IPC-2221 temperature rise, trace resistance, voltage drop, and power dissipation with dynamic cross-section preview in a responsive one-pager layout.

### 7. [LaserImagePrep.html](LaserImagePrep.html)
**Laser Engraving Grayscale & Dither Tool (One-Pager)**
- Client-side image preparation for laser engraving with drag-and-drop, interactive cropping, 90° rotation, and horizontal mirroring.
- Full tuning pipeline with RGB/HSV adjustments, edge enhancement (Sobel, Laplace, DoG), histogram levels, and laser dithering (Atkinson, Floyd-Steinberg, Stucki, Bayer, Threshold).
- 1-click material presets, interactive split comparison view, JSON configuration save/load, and full-resolution JPG/PNG export.

### 8. [GerberPreview.html](GerberPreview.html)
**Gerber & Excellon PCB Layer Viewer**
- Open individual Gerber and Excellon drill files, multiple files at once, or a complete PCB job packaged as a ZIP archive.
- Toggle and inspect color-coded copper, mask, silkscreen, paste, outline, and drill layers entirely in the browser.
- View board dimensions, cursor coordinates, layer summaries, and rendered primitive counts with pan, zoom, and fit-to-board controls.
