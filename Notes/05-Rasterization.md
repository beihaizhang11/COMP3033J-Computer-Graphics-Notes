# Rasterization
## Drawing Line
### Explicit form
Conceptually easy, but messy. (Use equation of line to connect points)
#### **Problems**:
* Doesn’t work for slope > 1; Doesn’t work when x1 < x0 or y1 < y0
* Use Bresenham’s Algorithm to solve
### Implicit/normal form
Easy, but lines not segments
### Parametric form
Easy to code
## Drawing Triangle
### Explicit form
Easiest to understand
### Half-plane (implicit)
Easiest to code
### Barycentric (parametric)
Computes weights for colour interpolation