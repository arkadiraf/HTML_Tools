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
**2-Layer 3-Phase Axial-Flux BLDC Stator Designer & Thermal Simulator**
- **Planar Stator Architecture**: Design axial-flux circular motor stators with configurable outer/inner diameters and stator coil counts (default 6 coils / 8 rotor magnets for balanced 3-phase BLDC operation).
- **Optimal Ratio Calculation**: Built-in torque-maximization solver applying theoretical optimum $D_{in} = D_{out} / \sqrt{3} \approx 28.8\text{ mm}$ for a $\varnothing 50\text{ mm}$ disk motor.
- **Centered Inter-Layer Via**: Transition via located at the exact geometric center ($r = R_{mid}$, $\theta = 0^\circ$).
- **Non-Intersecting Coils**: True 4-sided continuous trapezoidal sector spiral with uniform $6\text{ mil}$ ($0.152\text{ mm}$) trace width and clearance, with zero crossings or overlaps.
- **Rotor Magnet Overlay**: Visualizes 8 rotor magnets ($\varnothing 8.0\text{ mm}$) with alternating North (Red) and South (Blue) polarity aligned along the pitch circle.
- **5V DC Calculations**: Real-time evaluation of phase resistance, stall current at 5V, power dissipation, operating temperature rise, current density, and inductance.
- **JSON Configuration Save & Load**: One-click export and import of all motor parameters, with window drag-and-drop support.
- **CAD DXF Export**: Direct export of 2-layer copper traces (`COIL_L1`, `COIL_L2`), `BOARD_OUTLINE`, `PITCH_CIRCLE`, `VIA_PADS`, `VIA_DRILL`, and `ROTOR_MAGNETS_N`/`_S`.

### 6. [PCBTraceCalc.html](PCBTraceCalc.html)
**PCB Trace Resistance & Thermal Calculator (One-Pager)**
- IPC-2152 and IPC-2221 temperature rise, trace resistance, voltage drop, and power dissipation with dynamic cross-section preview in a responsive one-pager layout.
