# Interactive 3D Frame Rotation & Rotation Matrix Visualizer

An interactive 3D visualization tool for understanding coordinate-frame transformations, rigid-body rotations, and rotation matrices.

## Overview

This project visualizes two coordinate frames in 3D space:

- **Frame 0:** Fixed reference frame at the origin
- **Frame 1:** Movable frame whose position and orientation can be changed interactively

The tool provides real-time control of Frame 1 using translation and rotation sliders and displays the corresponding rotation matrix.

## Features

- Interactive 3D visualization of two coordinate frames
- Translation control along X, Y, and Z
- Rotation control about X, Y, and Z
- Real-time rotation matrix display
- Reset button to restore the initial configuration
- Color-coded coordinate axes:
  - X-axis → Red
  - Y-axis → Green
  - Z-axis → Blue
- Perspective grid for visualizing the 3D environment

## Controls

### Translation

Frame 1 can be translated along:

- X-axis
- Y-axis
- Z-axis

### Rotation

Frame 1 can be rotated about:

- X-axis
- Y-axis
- Z-axis

All values are updated interactively using sliders.

## Rotation Matrix

The displayed matrix represents the orientation of Frame 1 relative to Frame 0.

The matrix is updated in real time whenever the rotation sliders are changed.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Three.js

## How to Run

Open `index.html` in a modern web browser.

The project can also be deployed using GitHub Pages.

## Author

Kshitij Giri

IIT Gandhinagar
