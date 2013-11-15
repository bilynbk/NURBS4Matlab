NURBS4Matlab
============

NURBS Code for Matlab

A collection of classes for the creation, and manipulation of Non-Uniform Rational B-Splines (NURBS). The code is wrtten in Java, run in Matlab.

Usage:

1. Making java classes available to MATLAB.
   Put “nurbs.jar” in your project’s directory, and add following two lines to your Matlab file before using any NURBS Code function.

   javaaddpath(‘.\nurbs.jar’);
   import fq.geom.nurbs.*;

   Note: your only need run javaaddpath(…) once for a Matlab session.

   If you want better performance, you can add “nurbs.jar” to the static Java class path. See Matlab Document.

2. Create NURBS objects, and call the class’s methods to evaluate points, derivatives …

   There are some demos: curve_demo.m & surface_demo.m


