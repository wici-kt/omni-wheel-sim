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
- X/Y translation, rotation, and adjustable speed (0.5–10.0 m/s)
- Drag-free keyboard controls with WASD
- Live velocity and heading telemetry
- Animated wheel tread shows wheel movement while driving
- USB/Bluetooth gamepad support via the browser Gamepad API
  - Left stick: translate X/Y
  - Right stick X (or axis 3): rotate
  - Click the controller status button to scan/connect
- No build step required.
