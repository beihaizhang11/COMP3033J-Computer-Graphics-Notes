# 02

**Multiple Choice Questions (MCQs)**

1. Who invented Cartesian coordinates?
   a) Isaac Newton  
   b) René Descartes  
   c) Albert Einstein  
   d) Euclid  
   **Answer:** b) René Descartes

2. What does a vector measure?  
   a) Position  
   b) Direction and distance  
   c) Only distance  
   d) Only direction  
   **Answer:** b) Direction and distance

3. What is the result of Point - Point?  
   a) Point  
   b) Scalar  
   c) Vector  
   d) Undefined  
   **Answer:** c) Vector

4. Which product computes a scalar from two vectors?  
   a) Cross Product  
   b) Dot Product  
   c) Scalar Product  
   d) Matrix Product  
   **Answer:** b) Dot Product

5. A normalized vector has a length of:  
   a) 0  
   b) 1  
   c) 2  
   d) Undefined  
   **Answer:** b) 1

**True/False Questions**

1. The x-axis in standard coordinates usually runs from top to bottom.  
   **Answer:** False
2. Matrix multiplication is commutative.  
   **Answer:** False
3. Scalar multiplication can be performed on a Point.  
   **Answer:** False
4. A basis consists of independent vectors.  
   **Answer:** True
5. The identity matrix does not change the result of matrix multiplication.  
   **Answer:** True

# 03

### Multiple Choice Questions (MCQs)

1. What is the default value of coordinates in the Point class?
   - A) (1, 1, 1)
   - B) (0, 0, 0)
   - C) (0, 0)
   - D) Undefined
   - **Answer: B**
2. Which operation is undefined for Points?
   - A) Point + Vector
   - B) Point - Vector
   - C) Vector - Vector
   - D) Point + Point
   - **Answer: D**
3. What does the method `length()` in the Vector3f class return?
   - A) The area of the vector
   - B) The length of the vector
   - C) The magnitude of the vector
   - D) Both B and C
   - **Answer: D**

### True/False Questions

1. The Point class can be initialized with three coordinates.
   - **Answer: True**
2. Scalar multiplication is defined for Points.
   - **Answer: False**
3. Matrix multiplication can return a Point when multiplying a Point by a Matrix.
   - **Answer: False**
4. A Vector can be added to another Vector.
   - **Answer: True**

# 11 

1. What is the minimum frame rate the eye can perceive motion?
   a) 12 fps
   b) 16 fps
   c) 24 fps
   d) 30 fps
2. What is tearing in computer graphics?
   a) An image distortion
   b) Visual artifact from frame mismatch
   c) A type of animation
   d) A rendering technique
3. What does V-Sync do?
   a) Increases frame rate
   b) Eliminates tearing
   c) Enhances image quality
   d) Reduces input lag
4. How many bones does a typical human have?
   a) 206
   b) 208
   c) 210
   d) 202
5. What method is primarily used for character movement in animation?
   a) Keyframe interpolation
   b) Motion capture
   c) Inverse Kinematics
   d) Physics simulation

**Answers:**

1. c) 24 fps
2. b) Visual artifact from frame mismatch
3. b) Eliminates tearing
4. b) 208
5. c) Inverse Kinematics

# 12

**Multiple Choice Questions (MCQs):**

1. What type of radiation is light classified as?
   a) Sound waves
   b) Electromagnetic radiation
   c) Thermal radiation
   d) Mechanical waves
   **Answer:** b) Electromagnetic radiation
2. Which of the following best describes how light behaves?
   a) Only emitted
   b) Only absorbed
   c) Emitted, reflected, and absorbed
   d) Only refracted
   **Answer:** c) Emitted, reflected, and absorbed
3. What is the primary function of cones in the human eye?
   a) Low light vision
   b) Color vision
   c) Depth perception
   d) Night vision
   **Answer:** b) Color vision
4. What is the wavelength range visible to the human eye?
   a) 100 - 300 nm
   b) 350 - 700 nm
   c) 700 - 1000 nm
   d) 800 - 1200 nm
   **Answer:** b) 350 - 700 nm

**True/False Questions:**

1. Photons travel at the speed of light, which is approximately 3.00 x 10^8 m/s.
   **Answer:** True
2. Ray tracing is faster than projective rendering for real-time applications.
   **Answer:** False
3. The human eye can perceive wavelengths from 350 nm to 700 nm.
   **Answer:** True
4. Alberti’s Window is a technique for creating realistic 3D representations.
   **Answer:** True
5. Reflection occurs when a photon strikes a surface and bounces off.
   **Answer:** True

**1. What are the two types of cells in human eyes responsible for vision?**
A) Rods and Cones
B) Photons and Pixels
C) Pixels and Screens
D) Lenses and Corneas

**2. Which colour model is primarily used in printers?**
A) RGB
B) CMYK
C) HSV
D) YUV

**3. What does the Y component in YUV Colour Space represent?**
A) Hue
B) Saturation
C) Brightness
D) Intensity

**4. How is colour modulation defined?**
A) Mixing pigments
B) Reflecting all wavelengths
C) Subtracting light
D) Reflecting wavelengths common to both light and surface

**5. What is the primary function of a CCD in digital cameras?**
A) Capture images in black and white
B) Store energy per pixel
C) Emit light
D) Scan images

**Answers:**

1. A
2. B
3. D
4. D
5. B

# 14

**Multiple Choice Questions:**

1. What is a texture in computer graphics?
   a) A 3D model  
   b) An image painted on a surface  
   c) A type of lighting  
   d) A shading technique  
   **Answer:** b) An image painted on a surface

2. Which method is used for nearest neighbour interpolation?
   a) Using the average of surrounding values  
   b) Taking the nearest available texel  
   c) Linear interpolation  
   d) Color modulation  
   **Answer:** b) Taking the nearest available texel

3. What does clamping do in texture mapping?
   a) Repeats texture  
   b) Adjusts brightness  
   c) Limits texture coordinates to [0..1]  
   d) Changes texture resolution  
   **Answer:** c) Limits texture coordinates to [0..1]

**True/False Questions:**

1. T/F: Textures can only be used for geometric patterns.  
   **Answer:** False

2. T/F: Bilinear interpolation uses four nearest texels for color calculation.  
   **Answer:** True

3. T/F: OpenGL supports only 2D textures with (s, t) coordinates.  
   **Answer:** False

# 15

**Multiple Choice Questions (MCQs):**

1. What is the primary function of the surface normal in computer graphics?
   a) It determines color.
   b) It measures the angle of reflection.
   c) It defines the light source.
   d) It calculates shadow intensity.
   **Answer:** b) It measures the angle of reflection.
2. Which lighting model includes ambient, diffuse, and specular reflections?
   a) Phong Lighting Model
   b) Lambertian Model
   c) Blinn-Phong Model
   d) Fresnel Model
   **Answer:** a) Phong Lighting Model.

**True/False Questions:**

1. Ambient light is uniform and constant throughout the scene.
   **Answer:** True.
2. Shadows in OpenGL are automatically handled without any additional coding.
   **Answer:** False.

# 16

### Multiple Choice Questions (MCQs)

1. What does blending primarily involve?
   a) Combining entire images
   b) Combining geometric objects
   c) Storing images in frame buffers
   d) Creating textures
   **Answer:** b) Combining geometric objects
2. Which buffer is used for depth information in the frame buffer?
   a) Color buffer
   b) Depth buffer
   c) Stencil buffer
   d) Accumulation buffer
   **Answer:** b) Depth buffer
3. What function is used to enable alpha blending in OpenGL?
   a) glBlendFunc()
   b) glAlphaFunc()
   c) glClear()
   d) glDrawBuffer()
   **Answer:** a) glBlendFunc()

### True/False Questions

1. The accumulation buffer is used to combine multiple versions of a frame.
   **Answer:** True
2. The stencil buffer is used for color blending operations.
   **Answer:** False
3. Depth quantization can lead to rendering issues when objects are too close together.
   **Answer:** True
4. The scissor test allows for the discarding of fragments outside a specified rectangular region.
   **Answer:** True
5. Alpha blending should be done before drawing solid objects.
   **Answer:** False