# PSSI
Parametrized Surface Self-Intersection Routine

The goal of this project is to provide an implementation
of the GAIA european project reference algorithm for self-intersection.
It's an algorithm using surfaces with evaluators based on a standard
meshing of the surface. It was promoted as a reference method to compare
with into the GAIA project. Other methods in GAIA use the representation of 
the surface as Bezier or NURBS surfaces when they are of small degree.

An extension of the algorithm is to use bicubic patches instead of triangles 
that why there will be two routines in the code.
