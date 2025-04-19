# Three.js / React-Three-Fiber Projects

This repository is dedicated to my explorations in 3D web graphics using the Three.js library, primarily through the React-Three-Fiber (R3F) ecosystem. Discover interactive 3D scenes, data visualizations, animations, and other creative coding projects leveraging WebGL for rendering in the browser.

## Planned Projects (using React-Three-Fiber)

### 1. 3D Product Viewer
*   **Concept:** An interactive viewer for 3D models.
*   **Features:**
    *   Loading 3D models in glTF format (using `@react-three/drei`'s `useGLTF`).
    *   Allowing users to change model color/material via UI controls.
    *   Camera controls using `OrbitControls` (`@react-three/drei`).
    *   Basic scene lighting setup.

### 2. Procedural Terrain Explorer
*   **Concept:** A navigable, procedurally generated 3D landscape.
*   **Features:**
    *   Terrain mesh generation using a noise algorithm (e.g., `simplex-noise`).
    *   Navigation controls: First-Person Shooter style (`PointerLockControls`) or orbital (`OrbitControls`).
    *   Coloring or texturing the terrain based on elevation.

### 3. Animated Solar System
*   **Concept:** A simplified, animated model of a planetary system.
*   **Features:**
    *   Using basic geometries (spheres) and scene hierarchy for planets and moons.
    *   Orbital animations implemented using the `useFrame` hook.
    *   Applying basic textures to celestial bodies.
    *   A starfield background (e.g., using `Stars` from `@react-three/drei`).
    *   Camera control with `OrbitControls`.

*Note: The `.gitkeep` file in the root is a placeholder to ensure the main directory is tracked by Git, even when initially empty.* 