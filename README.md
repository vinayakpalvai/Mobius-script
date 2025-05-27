# Mobius-script
Python script that models a Mobius strip using parametric equations and computes key geometric properties.

Requirements : Define a MobiusStrip class that : Accepts: 
Radius R (distance from the center to the strip) 
Width w (strip width) Resolution n (number of points in the mesh)
number of points n Computes: A 3D mesh/grid of (x, y, z) points on the surface
Output:
Surface area (numerically, using integration or approximation)
Edge length (numerically along the boundary)

Parametric Equation of Mobius Strip :
x(u,v)=(R+v⋅cos⁡(u2))⋅cos⁡(u) y(u,v)=(R+v⋅cos⁡(u2))⋅sin⁡(u) z(u,v)=v⋅sin⁡(u2)
Where: => u∈[0,2π] => v∈[−w/2,w/2]

Deliverables : Python script (clean, modular, commented). 3D plot or screenshot (if you include visualization).

This assignment tests: 1) Parametric 3D modeling
2) Numerical integration / geometry 
3) Visualization 
4) Code clarity
