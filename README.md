
# Applied Geometry: B-Spline & Special Effects with Implementation

**B-Spline, Blending Spline, subdivision, shape deformation & special effects with source code**

---

## 🚀 Overview

This project demonstrates algorithms in geometric modeling and computer graphics centered around **B-splines**, **blending splines**, and associated **shape-changing / special effects** techniques. It includes both theoretical and practical implementation components, enabling experimentation with curve subdivision, blending, and dynamic deformation effects.

Key features:

- Implementation of B-spline curves (and possibly surfaces)  
- Blending spline / blending curve techniques  
- Subdivision / refinement of blended splines  
- Shape-change / morphing / special effects on curves  
- Integration with a library (e.g. **gmlib**) for geometry utilities  
- Example scenes/assets in the `assets` folder  
- Supporting documentation (e.g. “AppliedGeo.pdf”)  

---

## 📂 Project Structure

Here’s an overview of the main folders and files:
```bash
/
├── assets/ ← Images after getting output
├── gmlib/ ← Geometry / math library utilities
├── AppliedGeo.pdf ← Project documentation
├── README.md ←
└── [source files, .cpp/.h, etc.]

## 📐 Concepts & Algorithms

Here are the main concepts you’ll find in this project:

1. **B-Splines**  
   Fundamental spline curves defined by control points and knot vectors. You’ll find routines for evaluation, knot insertion, etc.

2. **Blending Splines / Curve Blending**  
   Techniques to smoothly connect or morph between spline segments, often used to create transitions or mixed shapes.

3. **Subdivision / Refinement**  
   Splitting or refining blended spline curves, often through recursive subdivision to increase detail or smoothness.

4. **Shape Change / Special Effects**  
   Applying dynamic transformations or deformations on spline curves — such as morphing, warping, or animated effects.

5. **Geometry Library (gmlib)**  
   Utilities for vector/matrix math, curve operations, transformations, etc. Radix of geometric computations used by the project.

These modules are tied together to showcase how advanced spline-based modeling and animations can be realized.

---


## 🛠 Dependencies & Requirements

To build and run this project, you’ll likely need:

- A C++ compiler (C++11 or newer)  
- Build system (e.g. CMake, Makefile)  
- Graphics framework (if you render visuals — e.g. OpenGL, GLFW, SDL, etc.)  
- Linear algebra / math library (some parts may use your gmlib or Eigen)  
- (Optional) Image / texture loading libraries depending on the visual demos  

_If you provide me with your exact dependencies or build scripts, I can refine this section._

---

## 💡 Building & Running


Here’s a generic setup that you can adapt:

1. Clone the repository:
   ```bash
   git clone https://github.com/sjb048/Applied_Geometry_B-Spline_special_effects-with-implementation.git
   cd Applied_Geometry_B-Spline_special_effects-with-implementation

2. Create a build directory and configure (if using CMake):

    mkdir build
    cd build
    cmake ..
    make

Configuration parameters — e.g. number of subdivisions, blending weights, deformation amount

Visualization — explain rendering viewport, how curves are drawn, shading, etc.

🧪 Testing & Validation

Validate your implementations against known B-spline examples (e.g. uniform knots, open curves)

Compare blending / subdivision results with reference implementations (if available)

Stress test with many control points or extreme parameter ranges

Unit tests for core math routines (vector ops, basis function evaluation, etc.)