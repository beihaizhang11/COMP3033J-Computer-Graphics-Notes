# 05-rasterization
## Barycentric (parametric)
α + β + γ = 1.0
## Comparison
- Explicit: conceptually easy, but messy
- Implicit: easy, but lines not segments
- Parametric: easy to code
## Tips:
- Clockwise winding means inside is on the right, counterclockwise means inside is on the left
- The half-plane test divides space into two regions for each line of the triangle
- Explicit doesn't work for slope > 1 and requires special handling

# 06-Geometric Modelling
- Union, subtraction, and XOR are all possible operations in CSG
- **Latitude** (φ) and **longitude** (θ) are used to define points on a sphere

Platonic Solid → All faces are same size and shape
Parametric Sphere → Uses latitude and longitude
Cylinder Approximation → Built from vertical strips

# 07-Projective Rendering
WCS → Reference frame for entire scene
OCS → Define object shape
VCS → Camera perspective

Translation → Moves object without changing orientation
Scaling → Changes size of object
Rotation → Changes orientation around 

- Z-buffering solves the visibility problem by keeping track of depth at each pixel.

# 08
- Matrix composition reduces the number of operations needed
- 