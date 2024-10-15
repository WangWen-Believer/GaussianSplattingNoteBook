### 3D Gaussian Ray Tracing: Fast Tracing of Particle Scenes

project page: https://gaussiantracer.github.io/

**Background**

Most existing methods render particles via rasterization, projecting them to screen space tiles for processing in a sorted order. The tile-based rasterizer is ill-suited to rendering from highly-distorted cameras with rolling shutter effects, which are important in robotics and simulation.

Ray Tracing Benefit: processing incoherent rays for secondary lighting effects such as shadows and reflections





#### Method

Accordingly, we design a customized GPU-accelerated ray tracer for Gaussian particles with a 𝑘-buffer [Bavoil et al. 2007] hits-based marching to gather ordered intersections, bounding mesh proxies to leverage fast ray-triangle intersections.

