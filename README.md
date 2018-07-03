# Kenney Particle Pack for Defold

ParticleFX effects for Defold made with the Kenney Particle Pack

If you use these you should move the sprites of each .particlefx to their own .atlas (you can have all share the same atlas). Try to have as small of an atlas, to have as few atlases as you can get. You can also resize the base size of the particle textures and then compensate in the initial size listed in the .particlefx files.

Particles / sprites which are tilted too much away from the camera need to have mipmaps disabled to keep texture clarity. There are provided material examples for this.

Click and drag to pan around. Scroll wheel to zoom. Spacebar to reset view/zoom.

Particles with more modifiers can be more expensive.

Some of the particles with modifiers are broken in engine due to an engine bug. Once the modifier bug is fixed in engine they should look like. For now inspect them in the editor or zoom in on them.