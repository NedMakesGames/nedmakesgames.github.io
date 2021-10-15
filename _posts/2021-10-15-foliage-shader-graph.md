---
title: 🌳 Translucent Foliage Shader Graph
tags: [Unity, Unity 2020.3, Unity 2021.1, Graphics Programming, URP, Shader Graph, HLSL, Shader, Math, Lighting, Foliage, Video, Article]
style: fill
color: secondary 
description: "Implement a foliage shader in Unity's URP Shader Graph, with double-sided rendering, translucency, and wind."
---

Plants, foliage and vegetation are really challenging to get right! It requires a custom made shader to tackle issues like translucency and wind. In this tutorial, I show how to create a foliage shader in the Unity URP (Universal Render Pipeline) Shader Graph. It supports all light types, shadows, and baked lighting, and includes several strategies for translucency, like separate normals for diffuse lighting and subsurface scattering. I also implement programmable wind animation and show a simple method to reconstruct normals. For grass billboards and tree leaf cards, I also demonstrate how to create double sided materials with normal map support.

***

{% include elements/video.html id="x4ufs1OzPIw" %}
*[YouTube](https://youtu.be/x4ufs1OzPIw) [Article](https://nedmakesgames.medium.com/creating-a-foliage-shader-in-unity-urp-shader-graph-5854bf8dc4c2) [Patreon](https://www.patreon.com/posts/57361644)*

![Lighting Math Explorer](https://i.imgur.com/LSHH1Sb.png "Lighting Math Explorer") 
Try out [Lighting Math Explorer](https://nedmakesgames.itch.io/lighting-explorer) to help visualize the lighting formulas showcased in this video.