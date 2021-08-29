---
title: 📏 Edge Detection Outlines
tags: [Unity, Unity 2020.1, Unity 2020.2, Unity 2020.3, Graphics Programming, URP, HLSL, C#, Shader, Renderer Feature, Outlines, Video]
style: fill
color: secondary 
description: "In this series, I investgate rendering grass using a compute shader to build meshes dynamically at runtime, incorporating level of detail into the mesh itself."
---

Outlines are a great way to add polish and style to a variety of games! In this tutorial, I show how to implement edge detection outlines in Unity Universal Render Pipeline using a combination of a shader graph and a renderer feature. Edge detection outlines can affect the entire screen or individual objects, do not change based on perspective, and can accentuate creases and changes in color!

This series contains four videos:
1. This video introduces edge detection outlines, creates the base shader graph, implements the sobel algorithm, and draws outlines based on color and depth across the entire screen.
2. This video adds normal edge detection to the outlines from video 1. It writes a depth-normals pass using a renderer feature. It also makes a variety of tweaks to the shader graph, making outlines more stable no matter where your camera views an object.
3. This video makes the outlines from video 2 apply to individual objects, supporting different outline colors for each. It removes the post-processing pass, but loses access to color data.
4. This video attempts to optimize the outlines from video 3 while keeping quality as high as possible.

***

{% include elements/video.html id="RMt6DcaMxcE" %}
Depth and color: *[YouTube](https://youtu.be/RMt6DcaMxcE) [Patreon](https://www.patreon.com/posts/files-depth-edge-47119072)* 

***

{% include elements/video.html id="fW-5srSHDMc" %}
Depth normals: *[YouTube](https://youtu.be/fW-5srSHDMc) [Patreon](https://www.patreon.com/posts/files-depth-edge-47165424)* 

***

{% include elements/video.html id="74AS5DmLe8w" %}
Individual objects: *[YouTube](https://youtu.be/74AS5DmLe8w) [Patreon](https://www.patreon.com/posts/files-individual-47204481)* 

***

{% include elements/video.html id="8Xq7tU5QN1Q" %}
Optimization: *[YouTube](https://youtu.be/8Xq7tU5QN1Q) [Patreon](https://www.patreon.com/posts/files-optimized-46784572)* 