# Raytracer
GPU based Raytracer

### How to use
- Make
- ./rt
- Select scene (find scene in scene directory)

### Controls
  - Translate : WASD Up Down
  - Rotate : 46 82 79
  - Screenshot : P
  - Quit : ESC
  
### Features
Multi-threaded architecture with opencl 1.2 in C with SDL2 and GTK, we use homemade parser for scene.
We can render sphere, negative sphere, plane, cone, cylinder, box, triangle, paraboloid and tore.
We can set 2 type of light, directional or point light, for specular reflection we used a cook torrance BRDF.
Object can have 4 differents materials: diffuse, reflective, refractive and transparant.
We can generate a perlin noise with marble or wood type, transform it into a bump map and apply it to a sphere.
For texture we can currently only apply it to a sphere.

4 objects : Plane, cylinder, cone, sphere

![alt text](https://github.com/thchin/Raytracer/blob/master/screenshots/screen1.bmp)

Bump mapped sphere with bump map generated from perlin noise

![alt text](https://github.com/thchin/Raytracer/blob/master/screenshots/screen2.bmp)

Triangle and cylinder

![alt text](https://github.com/thchin/Raytracer/blob/master/screenshots/screen3.bmp)
