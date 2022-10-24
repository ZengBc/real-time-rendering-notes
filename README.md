# real-time-rendering-notes
## The Graphics Rendering Pipeline

The heart of real-time rendering is the set of steps that takes a scene description and converts it into something we can see.

## The Graphics Processing Unit

The modern GPU implements the stages of the rendering pipeline using a combination of fixed-function and programmable units.

## Transforms

Transforms are the basic tools for manipulating the position, orientation, size, and shape of objects and the location and view of the camera.

## Shading Basics

Discussion begins on the definition of materials and lights and their use in achieving the desired surface appearance, whether realistic or stylized. Other appearance-related topics are introduced, such as providing higher image quality through the use of antialiasing, transparency, and gamma correction.

## Texturing

One of the most powerful tools for real-time rendering is the ability to rapidly access and display images on surfaces. This process is called texturing, and there are a wide variety of methods for applying it.

## Shadows

Adding shadows to a scene increases both realism and comprehension. The more popular algorithms for computing shadows rapidly are presented.

## Light and Color

Before we perform physically based rendering, we first need to understand how to quantify light and color. And after our physical rendering process is done, we need to transform the resulting quantities into values for the display, accounting for the properties of the screen and viewing environment. Both topics are covered in this chapter.

## Physically Based Shading

We build an understanding of physically based shading models from the ground up. The chapter starts with the underlying physical phenomena, covers models for a variety of rendered materials, and ends with methods for blending materials together and filtering them to avoid aliasing and preserve surface appearance.

## Local Illumination

Algorithms for portraying more elaborate light sources are explored. Surface shading takes into account that light is emitted by physical objects, which have characteristic shapes.

## Global Illumination

Algorithms that simulate multiple interactions between the light and the scene further increase the realism of an image. We discuss ambient and directional occlusion and methods for rendering global illumination effects on diffuse and specular surfaces, as well as some promising unified approaches.

## Image-Space Effects

Graphics hardware is adept at performing image processing at rapid speeds. Image filtering and reprojection techniques are discussed first, then we survey several popular post-processing  effects: lens flares, motion blur, and depth of field.

## Beyond Polygons

Triangles are not always the fastest or most realistic way to describe objects. Alternate representations based on using images, point clouds, voxels, and other sets of samples each have their advantages.

## Volumetric and Translucency Rendering

The focus here is the theory and practice of volumetric material  representations and their interactions with light sources. The simulated phenomena range from large-scale atmospheric effects down to light scattering within thin hair fibers. 

## Non-Photorealistic Rendering

Attempting to make a scene look realistic is only one way of rendering it. Other styles, such as cartoon shading and watercolor effects, are surveyed. Line and and text generation techniques are also discussed.

## Polygonal Techniques

Geometric data comes from a wide range of sources, and sometimes requires modification to be rendered rapidly and well. The many facets of polygonal data representation and compression are presented.

## Curves and Curved Surfaces

More complex surface representations offer advantages such as being able to trade off between quality and rendering speed, more compact representation, and smooth surface generation.

## Pipeline Optimization

Once an application is running and uses efficient algorithms, it can be made even faster using various optimization techniques. Finding the bottleneck and deciding what to do about it is the theme here. Multiprocessing is also discussed.

## Acceleration Algorithms

After you make it go, make it go fast. Various forms of culling and level of detail rendering are covered.

## Efficient Shading

A large number of lights in a scene can slow performance considerably. Fully shading surface fragments before they are known to be visible is another source of wasted cycles. We explore a wide range of approaches to tackle these and other forms of inefficiency while shading.

## Virtual and Augmented Reality

These fields have particular challenges and techniques for efficiently producing realistic images at rapid and consistent rates.

## Intersection Test Methods

Intersection testing is important for rendering, user interaction, and collision detection. In-depth coverage is provided here for a wide range of the most efficient algorithms for common geometric intersection tests.

## Graphics Hardware

The focus here is on components such as color depth, frame buffers , and basic architecture types. A case study of representative GPUs is provided.
