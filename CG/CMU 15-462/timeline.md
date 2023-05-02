CMU 15-462/662 (Computer Graphics)

Lecture 20 finished, goto https://www.youtube.com/watch?v=Fi9xu3z97W4&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=22

Lecture 20 Animation

All kinds of Splines

Lecture 19 finished, goto https://www.youtube.com/watch?v=XVTw68iHef0&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=22

lecture 19 Variance Reduction

Lecture 18 finished, goto https://www.youtube.com/watch?v=IQhLk_XaFc8&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=20

Lecture 18 Monte Carlo Rendering

Lecture 17 finished, goto https://www.youtube.com/watch?v=FUZJNlRqrAc&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=19

Lecture 17 Numerical Integration

Gauss Quadrature
Trapezoid rule
Monte Carlo Integration
PDF
Cumulative distribution function

Lecture 16 finished, goto https://www.youtube.com/watch?v=EGNZm9m382s&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=18

Lecture 16 The rendering equation

different reflection functions

Lecture 15 finished, goto https://www.youtube.com/watch?v=Ttxdbn7TSLI&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=17

Lecture 15 Radiometry

Lecture 14 finished, goto https://www.youtube.com/watch?v=5lGYm8L_rfo&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=16

Lecture 13 finished, goto https://www.youtube.com/watch?v=77WBg0Mprt0&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=15

Lecture 13 Spatial Data Structures

BVH
K-D tree
octree

Lecture 12 finished, goto https://www.youtube.com/watch?v=NF7r-pC8fFc&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=14
Lecture 12 Geometric Queries

Distance of point to line, to line segment
Closest point in triangle

Ray-intersections: sphere plane triangle
mesh-mesh intersection
intersection
- point-point
- point-line
- line-line
- triangle-triangle

Lecture 11 finished, goto https://www.youtube.com/watch?v=GPPyUT9Pytw&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=13

Lecture 11 Geometry Processing

Subdivision
Edge Collapse (quadric error metric) sum of squared point-to-plane distances
positive definition
Delaunay

Lecture 10 finished, goto https://www.youtube.com/watch?v=BwpEoZYcrwY&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=12

Lecture 10 Meshes and Manifolds

Polygon soup
Adjacency List: vertices and polygons with vertices index

Incidence Matrices: most of values are zero, use sparse matrices. Hard to change connectivity, since it used fixed indices. Mesh does not have to be manifold.

Halfedge data structure
design halfedge-type data structures: http://geometry-central.net/

Lecture 9 finished, goto https://www.youtube.com/watch?v=HePDHsp8spU&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=11

Lecture 9 Introduction to geometry

- EXPLICIT
- IMPLICIT

Bernstein Basis
curves


Lecture 8 finished, goto https://www.youtube.com/watch?v=MakhXtIX2YM&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=10

Lecture 8 Depth & Transparency

premultiplied alpha

Pipeline wrap up

 https://www.youtube.com/watch?v=WtYfF48Z9mA&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=9

Lecture 7 Perspective Project &  Texture Mapping

Small clip range to avoid z-fighting

Perspective transform http://www.songho.ca/opengl/gl_projectionmatrix.html

Barycentric Coordinates

Perspective-Correct interpolation. interpolate in 3D space

Texture mapping
- normal
- displacement

Texture sampling (magnification)
- nearest neighbor
- bilinear interpolation

Texture refiltering

mip map
- Trilinear interpolation: interpolate between different mip map level with bilinear interpolation

Anisotropic Filtering
interpolation more mip map level

Lecture 6 finished, goto https://www.youtube.com/watch?v=_4Q4O2Kgdo4&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=8

Lecture 6 3D rotation

latitude & longitude

Euler Angles, Gimbal lock

Complex number

Complex multiplication:
- angles add
- magnitudes multiply

Quaternions:
Scalar + Vector From

[Lie algebras]

Maybe I will review this lecture later (for Quaternions).


Lecture 5 finished, goto https://www.youtube.com/watch?v=YF5ZUlKxSgE&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=7

Lecture 5: basic transformations

Decomposition of linear transformations

Polar & Singular value decomposition
Interpolating transformation [Shoemake & Duff "Matrix Animation and Polar Decomposition]

Homogeneous Coordinates

Lecture 4 finished, Goto https://www.youtube.com/watch?v=QmFBHSJS0Gw&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=6

Lecture 4: Rasterization

Triangle is the primitive.
Coverage via sampling
Aliasing!
Nyquist-Shannon theorem

Image artifacts:
- "Jaggies" in a static image
- "Roping" or "shimmering" when animated
- Moire patterns in high-frequency areas

Point-in-triangle test
three half-plane test
incremental traversal
parallel coverage test, test all samples in triangle bounding box in parallel.
Tiled triangle traversal
Hierarchical strategies!

Lecture 3 finished, Goto https://www.youtube.com/watch?v=B0hsT2npIc0&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=5

Lecture 3: triple product formula: det(u,v,w) =  dot(cross(u,v) ，w)

Differential Operators

Gradient
La Gardient is hard for me, but it is useful.

Laplacian & Hessian

Lecture 2 finished, Goto https://www.youtube.com/watch?v=O7Bec2uX3ZQ&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=4

Lecture 2:
L2 Norm of functions

numerical integration (Later on)

Inner Product

Wait to watch linear maps.

Gram-Schmidt to find orthonormal basis from a collection of basis vector.

Fourier Transform Fourier decomposition

Linear Equation


Lecture 1 watched, please watch: https://www.youtube.com/watch?v=2c8XQlQApx8&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&index=3

Lecture 1:
Is start with history of different computer monitors, From no display to PDP-1 to nowadays 8k monitor.

They show us SIGGRAPH 2020 Technical Papers Trailer.
And play full video.

Time to modeling and drawing a cube.

Learning Perspective projection.

Rasterization to depict a line. Diamond rule to test pixel and line.
Incremental line rasterization.

Introduce watched, please watch: https://youtu.be/W6yEALqsD7k?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E&t=146

ready to start: https://www.youtube.com/watch?v=W6yEALqsD7k&list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E
