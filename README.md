# CS 330 Computational Graphics and Visualization Portfolio Project

## Project Overview

This repository contains my final project for CS 330: Computational Graphics and Visualization. The project is a 3D gaming desk setup built in C++ and OpenGL. The scene was based on my Milestone One concept image and evolved through each course milestone as I added object modeling, camera navigation, textures, lighting, and final polish.

The final scene includes a desk surface, gaming controller, monitor, keyboard, mouse, and RGB tower PC. The controller is the main complex object in the scene and was built using multiple primitive shapes, including boxes, cylinders, spheres, and torus shapes. The final version also includes a realistic wood desk texture, textured controller materials, monitor glow, RGB lighting from the PC tower, and subtle LED accents around the desk edge.

## Repository Contents

- `CS330_Final_Project_Gaming_Desk_Setup_Final_Polish_V2.zip`  
  Final 3D scene project files for Visual Studio, including the C++ and OpenGL source code.

- `CS330_Final_Project_Design_Decisions.docx`  
  Written design decisions document explaining the development approach, object choices, navigation controls, and modular code structure.

## Reflection

### How do I approach designing software?

I approach software design by starting with the overall goal and then breaking the project into smaller parts that can be built, tested, and improved. For this project, I began with a gaming desk concept because it connected to my interests in technology and gaming while still giving me realistic objects to recreate with basic 3D shapes. Instead of trying to build everything perfectly from the start, I focused on creating a scene that could grow through each milestone.

This project helped me strengthen my ability to think visually and structurally at the same time. I had to look at real-world objects and decide which basic shapes could represent them in OpenGL. For example, the controller was not one single object. It needed a body, grips, buttons, thumbsticks, triggers, and small accent details. That pushed me to think about how multiple simple shapes can work together to create something recognizable.

The design process I followed was iterative. I started with the proposal and rough sketch, then built the controller, added the plane, expanded the scene with more desk objects, applied textures, and finally refined the lighting and scale. That approach can be applied to future work because it keeps large projects manageable. Breaking a project into smaller pieces makes it easier to test progress, catch issues early, and improve the final result through feedback.

### How do I approach developing programs?

When developing programs, I try to build a working foundation first and then improve it through focused revisions. In this project, that meant getting the basic shapes visible first before worrying about textures, lighting, or camera controls. Once the scene was functional, I could refine the object placement, adjust scale, add materials, and improve the overall presentation.

A major development strategy I used was modularizing the scene. Instead of treating everything as one large block of code, I organized the project with reusable functions for transformations, materials, textures, lighting, and individual scene objects like the keyboard and mouse. This made the code easier to read and easier to adjust when objects needed to be resized, repositioned, or polished.

Iteration was a major part of the project. The controller, lighting, keyboard, mouse, desk texture, and LED accents all changed over time. Some early versions technically worked but did not look right visually. Each revision made the scene more balanced and more recognizable. My approach to development evolved from simply trying to make objects appear on screen to thinking more carefully about scale, readability, lighting, user navigation, and how the scene would look from different camera angles.

### How can computer science help me in reaching my goals?

Computer science helps me reach my goals by giving me the tools to solve technical problems creatively. This project showed me how programming can be used to build visual, interactive environments instead of only working with data or backend logic. Computational graphics gave me a better understanding of how math, programming, and design come together to create something a user can explore.

In my educational pathway, this project gave me more confidence working with C++, OpenGL, transformations, shaders, textures, lighting, and camera systems. These are skills I can build on in future courses because they connect directly to problem solving, spatial reasoning, and interactive application development.

Professionally, computational graphics and visualization are valuable because they strengthen the way I think about user experience, visual communication, and technical implementation. Even though my career interests are also connected to DevOps, automation, and AI-driven tools, this project helped me practice breaking complex systems into smaller components, testing changes through iteration, and presenting technical work in a polished way. Those skills apply far beyond graphics and can support my long-term growth as a developer and engineer.
