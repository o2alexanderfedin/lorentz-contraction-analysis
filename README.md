# Lorentz Contraction Analysis Package

**Author:** Alexander Fedin  
**ORCID:** [0009-0000-7127-6635](https://orcid.org/0009-0000-7127-6635)

## Overview

This repository contains a comprehensive analysis of Lorentz contraction in special relativity, challenging the standard interpretation through rigorous kinematic analysis and interactive visualizations.

## Contents

### 📄 LaTeX Document
- `lorentz_contraction_fedin.tex` - Main theoretical paper
- `lorentz_contraction_fedin.pdf` - Compiled PDF version

**Abstract:** The paper demonstrates that when initial conditions and measurement procedures are rigorously defined within a single inertial frame, no contraction is observed. The Lorentz contraction emerges only when coordinates are transformed between frames using relativity of simultaneity.

### 🎯 Interactive Visualizations

#### 1. Relativistic Particle Motion (`relativistic_particle_motion.html`)
- Tracks point object P₀ through acceleration and uniform motion
- Shows three key time points (T₀, T₁, T₂) and positions (X₀, X₁, X₂)
- Displays real-time Lorentz factor calculations
- Default velocity V₁ = c/2 (50% speed of light)
- Three synchronized graphs:
  - Position vs Time
  - Velocity vs Time  
  - Distance from X₀ vs Time

#### 2. Laser Interferometer (`laser_interferometer.html`)
- Demonstrates perpendicular beam detection system
- Shows how simultaneous measurements are made in observer's frame
- Interactive controls for object length, velocity, and mirror positions
- Visualizes the measurement process with animations

#### 3. Simultaneity Detector (`simultaneity_detector.html`)
- Illustrates how simultaneity is frame-dependent
- Interactive demonstration of Einstein's train thought experiment
- Shows light signal propagation from events to central detector
- Adjustable parameters for event timing and observer velocity

#### 4. Point Particle Motion (`point_particle_motion.html`)
- Non-relativistic version for comparison
- Clear visualization of acceleration and uniform motion phases
- Helpful for understanding the basic kinematics before relativistic effects

## Key Physics Concepts

### Motion Profile
1. **Phase 1 (T₀ to T₁):** Constant acceleration G
   - Position: x(t) = X₀ + ½G(t-T₀)²
   - Velocity: v(t) = G(t-T₀)

2. **Phase 2 (T₁ to T₂):** Uniform motion at V₁
   - Position: x(t) = X₁ + V₁(t-T₁)
   - Velocity: v = V₁ = G(T₁-T₀)

3. **Phase 3 (t > T₂):** Continuing uniform motion
   - Position: x(t) = X₂ + V₁(t-T₂)

### Relativistic Effects at V₁ = c/2
- Lorentz factor: γ = 1.155
- Time dilation: 15.5%
- Length contraction: 13.4%

## How to Use

1. **View the Paper:** Open `lorentz_contraction_fedin.pdf` to read the theoretical analysis

2. **Run Visualizations:** Open any HTML file in a modern web browser
   - No installation required
   - Works offline
   - Interactive controls for all parameters

3. **Compile LaTeX:** If you want to modify and recompile the paper:
   ```bash
   pdflatex lorentz_contraction_fedin.tex
   ```

## Technical Requirements

- **For visualizations:** Any modern web browser (Chrome, Firefox, Safari, Edge)
- **For LaTeX compilation:** TeX distribution (MacTeX, MiKTeX, or TeX Live)
  - Required packages: amsmath, physics, hyperref, tikz, geometry

## License

This work is provided for educational and research purposes. Please cite appropriately if using in academic work.

## Contact

For questions or discussions about this work, please reference the ORCID profile above.

## Acknowledgments

Visualizations created with HTML5 Canvas and JavaScript for interactive physics demonstrations.