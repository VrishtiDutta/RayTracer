# RayTracer

## Background:
This ray tracer basically "paints an image" based on a hypothetical scene set up in the viewpoint of e (as depicted below).  

<center> <img src="RayTracingDiagram.png"/> </center>  
  
This image is created by shooting a ray through the image screen to the scene to colour each pixel on the screen using it's reflection.
  
These hypothetical objects (T<sub>1</sub>, T<sub>2</sub>, T<sub>3</sub>) in the diagram each have an original colour (described as ambient). But how the colour is perceived to the eye e (i.e. painted onto the image screen) depends on a variety of factors, but all rely on the basic understanding of light reflections. The ray directed from e to the object hits the object surface in the direction of the light source (called shadow ray or diffusion), denoted as vector L. However, the ray also bounces off to hit another object in the scene which reflects back on the original object, denoted vector R.  

Phong's Illumination Model sums up the combination of these characteristics using a simple formula:

<center> <img src="PhongsIlluminationDiagram.png"/> </center>  
<center> <img src="PhongsIlluminationFormula.png"/> </center>  


