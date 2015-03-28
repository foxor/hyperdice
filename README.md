# Hyperdice
Application for simulating and rendering the rolling of n-dimensional dice

# Purpose
This project is an opportunity for me to stretch my C++ legs, and learn more about:
 * Physics simulation
 * Quaternion number spaces
 * Alternate geometrical projections
 * SDL
 * Tesselation
 * Procedeural geometry

# Technologies
I'm building this in C++, using SDL.  Clang compiles to LLVM, and emscripten cross-compiles to asm.js.  A web browser compiles to native.

I'm using a dual "quaternion" number system to represent the position and rotation of the objects.  I believe that each quaternion will have n+1 elements, where n is the dimension.

# Roadmap
 1. Emscripten hellow world
 2. Draw a triangle
   * Use a fake coordinate system
 3. Move the triangle
   * Use the real coordinate system
 4. Procedeurally generate a cube
 5. Cube falls to the ground
 6. Upgrade rendering to draw n-dimensional cube
 7. Allow user to "roll" the cube
