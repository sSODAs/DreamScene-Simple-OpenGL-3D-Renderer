# DreamScene-Simple-OpenGL-3D-Renderer

<img src="images/preview.png" width="400">

DreamScene is a small **Modern OpenGL (C++) project** that renders a 3D scene using custom shaders, lighting, and camera controls.

This project was created as part of a university graphics assignment with the theme **“MY DREAM”**, focusing on understanding the fundamentals of 3D rendering rather than building a full engine.

## Overview
The application starts by sending vertex data and mesh information to the GPU, where all rendering is handled through the modern OpenGL pipeline. Custom vertex and fragment shaders are responsible for transforming the geometry from model space to screen space and applying basic lighting calculations.

A perspective camera is implemented to allow scene navigation, with keyboard input controlling movement and mouse input controlling the viewing direction. Textures are loaded at runtime using stb_image and applied to the 3D models during rendering.

Lighting is calculated in the fragment shader on a per-pixel basis, using the current light position and camera position to produce basic shading effects across the scene.

## What This Project Does
- Creates an 800 × 600 OpenGL window
- Renders a textured 3D model
- Applies basic lighting calculations in shaders
- Uses custom vertex and fragment shaders
- Supports camera movement and mouse look
- Draws a simple animated background using shaders

## Technologies Used
- C++
- Modern OpenGL (Core Profile)
- GLFW (Window & Input)
- GLEW (OpenGL Extension Loader)
- GLM (Math Library)
- stb_image (Texture Loading)

## Controls
- **W / A / S / D** – Move camera
- **Mouse** – Look around
- **Space / Left Shift** – Move up / down
