# Archviz-Litterbug-Den
Attempt of architectural realtime vizualisation using Blender and Armory3d (Work in progress)

Furniture models are mainly from Sweethome 3D, eTeks. Check licensing here: https://www.sweethome3d.com/license.jsp and/or here
https://creativecommons.org/licenses/by/3.0/

I have adapted some of the models. First person controls WASD + mouse, Blinds are functional, control with keyboard numbers 1..6.
There will be two versions. One with settings adapted for the OS from Redmond (DirectX) sporting Voxel AO and another one for Linux
OpenGL, where Voxel AO does not seem to be (yet?) supported by Armory3D. Resulting in different settings for example concerning the world sky texture strength.
I have so far uploaded the windows version as a blend file, as i am still trying to get Voxel AO to work on LINUX. Should you run Linux, you could still use this blend file, but the lighting will be off. For Linux, I recommend changing the sky texture to a dark environment texture without lots of reflections and play with the strength settings till you like it. Adjust the air turbidity for the volumetric lighting in Armory render settings, till the strength of the god rays appear OK to your eyes. To run the blend you will need Blender 2.93.7 with Armory3d SDK (as of December 2021) installed. Then just press F5.
