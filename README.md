## Student Info
Name: Francisco Diaz
Email: fd86@nau.edu
Class: CS 430

## Usage
This program takes 4 commands: The length, width, the CVS file, and the output PPM file. This version of the raytracer will know take in a light primitive that will be used to shade
the objects in the scene. It will do this by calculating the diffuse, specular, radial attenuation, and angular attenuation(If its a spot light it will change) and adding it to the color.


###Example command line input
./raycast 100 100 test.csv output.ppm

## Known Issues
I had an issue with implementing the shadows of the objects. When I tried it it would either make the sphere black or it would just make half the sphere and the plane black. I was not sure on how to fix
this issue. When redering a spot light I did notice a difference but I am not sure if function properly. My last issue is that for my parser to work you can not have a return character in the middle of the data.
It will only work if the data for the primitive is in one line. 