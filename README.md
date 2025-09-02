## Computational-Geometry

This project explores computational geometry through interactive visualizations of polygons and point sets. The main focus is on different methods of triangulation and related geometric structures, implemented in Python and visualized with Plotly and ipywidgets.

# Features

Convex Hull Construction – compute and display convex hulls of a set of points.

Convex Hull Triangulation – triangulate convex hull polygons.

Triangle-Splitting Triangulation – recursively split triangles to incorporate interior points.

Delaunay Triangulation – generate Delaunay triangles with optional circumcircles.

Medial Axis Visualization – compute and display the medial axis of strictly convex polygons.

Interactive Widgets – change input points, toggle between triangulation methods, and adjust axes ranges in real-time.

# Requirements

Python 3.9+

Plotly

ipywidgets

NumPy

SymPy
 (for medial axis / line intersection logic)

SciPy
 (for Delaunay triangulation)

# Algorithms Implemented

Convex Hull (Graham Scan)

Convex Hull Triangulation

Triangle-Splitting Triangulation

Delaunay Triangulation (via SciPy)

Circumcircle Calculation

Medial Axis Approximation 
