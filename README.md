# OmniLab — Omni Wheel Car Simulator

A browser-based holonomic drive playground. Configure a rectangular or triangular chassis, adjust the angle of every wheel, add wheels (minimum 3), and drive the live vector simulation with sliders or **WASD**.

## Run locally

No build step is required. Serve the folder with any static server:

```bash
python3 -m http.server 4173
```

Open <http://localhost:4173>.

## Features

- 3+ adjustable omni wheels
- Per-wheel roller angle controls
- Rectangular and triangular chassis layouts
- Width and length tuning
- X/Y translation and rotation drive vectors
- Drag-free keyboard controls with WASD
- Live velocity and heading telemetry
- Responsive visual interface
