# Volumetric Clouds

This is a demo implementing one way of drawing volumetric
cloudscapes in Godot sky shaders.

This demo uses animated clouds generated from ray marching
3D textures. It features automatic time of day adjustments
just by rotating the sun.

Renderer: Vulkan

## Screenshots

![Screenshot](screenshots/Midday.png)

![Screenshot](screenshots/Dusk.png)

![Screenshot](screenshots/Sunset.png)

# The modification I made was wrote into clouds.gdshader

In short,fixed a small reset problem of orginal demo and added
a positional jitter to raymarch
