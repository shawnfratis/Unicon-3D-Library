Shawn Fratis' Unicon 3D Library 
(shawnfratis@gmail.com)
(https://unicon.sourceforge.io/)

These are all "modules" from my 3D software broken out as individual programs in order to demonstrate Unicon 3D capabilities. Each program comes provided with a window to view the running program. A single texture map is included that applies to all programs.

Any of the variables can be changed or altered for your own purposes.

############################################################ 

texcylinder.icn

Creates a single 3D cylinder with texture map applied.

############################################################

texplane.icn

Creates a single 3D plane with texture map applied.

############################################################

texsphere.icn

Creates a single 3D sphere with texture map applied.

############################################################

texvoxcube.icn

Creates a cube where a different texture map can be applied to each facet.
Also, random or non-random voxel-like distributions can be created.

############################################################

texterrain.icn

Creates a plane where a single texture map is applied, but vertices within the plane can be moved in the y-axis randomly or non-randomly to create a terrain effect.
NOTE: some of this code can probably be condensed but as of yet I haven't came up with a method for this. However, the code as it is works ok.

############################################################

pointgrid.icn

Creates a point array in 3 dimensions with a graduated color across the points.
NOTE: This takes a while to process (1-2 minutes depending on your processor).

############################################################ 

noglterrain.icn

Creates different random 3D terrains, which can be output to an image.
NOTE: This doesn't use OpenGL. It uses X-Windows only.

############################################################

noglshapes.icn

Creates various 3D shapes which an be animated by using the mouse.
NOTE: This doesn't use OpenGL. It uses X-Windows only.

############################################################

