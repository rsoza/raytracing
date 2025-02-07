# Ray Tracing in One Weekend - Follow Along

This repository is a personal follow-along implementation of the book _Ray Tracing in One Weekend_ by Peter Shirley. The goal is to build a ray tracer from scratch while understanding the fundamental concepts of computer graphics and rendering.

## About the Book

_Ray Tracing in One Weekend_ is part of a series of books that introduce ray tracing through a hands-on approach. The book walks through building a simple yet powerful ray tracer using C++.

The official book series can be found here: [Ray Tracing in One Weekend](https://raytracing.github.io/)

## Features Implemented

- Basic ray generation
- Sphere rendering
- Camera implementation
- Antialiasing
- Diffuse and reflective surfaces
- Scene building with multiple objects
- Lambertian, metal, and dielectric materials
- Monte Carlo sampling techniques

## Requirements

- C++ compiler (GCC)
- CMake (optional for build automation - i am not using it)

## Building the Project

1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd ray_tracing_one_weekend
   ```
2. Compile the code using a C++ compiler:
   ```sh
   g++ -o raytracer main.cpp
   ```
3. Run the program:
   ```sh
   ./raytracer
   ```

## Future Plans

- Implement additional features from _Ray Tracing: The Next Week_
- Optimize performance with multi-threading
- Add support for textures and lighting models

## References

- _Ray Tracing in One Weekend_ series: [https://raytracing.github.io/](https://raytracing.github.io/)
- Peter Shirley's GitHub: [https://github.com/petershirley](https://github.com/petershirley)
