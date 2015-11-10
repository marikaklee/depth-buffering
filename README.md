# Shaded-Rendering-And-Depth-Buffering

The following is implemented as part of this project:

1. My own implementation of the depth-buffer algorithm for triangles, assuming an orthographic camera model.

2. Rotation and translation of the camera, rotation, scaling, and translation of objects.

3. Generated triangle meshes solid objects with vertex normals: Ellipsoid, Sphere, Cylinder with end caps, Box, Torus

4. My own  implementation of polygon rendering methods: <br>

  i. Flat surface rendering – compute the triangle plane normal for this <br>
  ii. Gouraud rendering – interpolate vertex colors determined by lighting equation <br>
  iii. Phong rendering – interpolate normal and apply lighting equation at each pixel
  
  As well as a keyboard interface that allows the user to change rednering method: F, G, P
  
5. Implementation of illumination equation (combined diffuse, specular, and ambient) and demonstration of the lighting model and colored lights in the five different scenes you define, with 3 differently shaped solid objects and at least 2 lights in each scene. <br>

  i. Point light source<br>
  ii. Infinite light source<br>
  iii. Ambient light source<br>
  iv. Attenuation: radial and angular<br>
  
  As well as  a keyboard interface that allows the user to toggle on/off specular term, diffuse term, ambient term: S, D, A.
  And a  a keyboard interface that allows the user to toggle on/off each of the lights in your scene model: Hit L key, then 1, 2, 3, 4, etc., to identify which light to toggle on/off.
  
6. Defined materials and their properties:

  i. Coefficients of reflection for each color channel (R,G,B): ka, kd, ks<br>
  ii. Specular exponent: ns<br>
 
  As well as a keyboard interface to change the materials for solid objects in the scene model and redisplay.
