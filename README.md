# Lorentz Contraction Analysis Package

**Author:** Alexander Fedin  
**ORCID:** [0009-0000-7127-6635](https://orcid.org/0009-0000-7127-6635)

## 🎯 Live Interactive Visualizations

**[View All Visualizations Here](https://o2alexanderfedin.github.io/lorentz-contraction-analysis/)**

## Overview

This repository contains a comprehensive analysis of Lorentz contraction in special relativity, demonstrating that the effect is best understood as **an artifact of the measurement apparatus** rather than a physical deformation.

## Key Insight: Lorentz Contraction as a Measurement Artifact

Our analysis reveals that Lorentz contraction is not a physical compression of objects, but rather an artifact arising from the measurement procedure:

### Why It's a Measurement Artifact:

1. **Simultaneity Convention**: The "contraction" only appears when measuring both endpoints simultaneously in the observer's frame—which means non-simultaneous events in the object's rest frame.

2. **No Physical Deformation**: When two particles undergo identical acceleration (synchronized in the observer's frame), they maintain constant separation D throughout all motion phases.

3. **Coordinate Artifact**: The contraction emerges from the Lorentz transformation's redefinition of simultaneity between frames—it's how we map events between coordinate systems, not a physical change.

4. **Operational Definition**: The measured "length" depends entirely on the operational definition of simultaneity in the measurement procedure.

### The Measurement Creates the Effect:

- Different measurement procedures (different simultaneity conventions) yield different results
- The measurement apparatus in one frame captures different time slices of the object's worldline
- The "contracted length" is what you measure when applying a specific simultaneity convention
- Our beam splitter experiments prove particles maintain constant separation with equal optical paths

## Contents

### 📄 LaTeX Document
- `lorentz_contraction_fedin.tex` - Main theoretical paper
- `lorentz_contraction_fedin.pdf` - Compiled PDF version

**Key Finding:** When initial conditions and measurement procedures are rigorously defined within a single inertial frame, no contraction is observed. The Lorentz contraction emerges only as a coordinate artifact when transforming between frames with different simultaneity conventions.

### 🎯 Interactive Visualizations

All visualizations feature **continuous auto-play animations** that demonstrate the physics concepts without requiring user interaction.

#### Classic Lorentz Theory
- **Classic Interpretation** - Standard textbook rod experiment
- **Classic Measurement** - How the standard theory measures contracted length
- **Classic Simultaneity** - Demonstration of relativity of simultaneity

#### New Analysis - Constant Separation (Step-by-Step)
1. **Single Particle Motion** - Basic relativistic motion with γ factor
2. **Laser Detection** - P₀ with laser triggering at T₀ and detection at T₂
3. **Interferometer** - Perpendicular beam detection principles
4. **Two Particles** - P₀ and P₁ maintaining constant separation D
5. **Key Result** - Beam splitter with equal optical paths proves constant D


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