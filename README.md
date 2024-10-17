# openGL
This is a repository for me to upload my progress in learning openGL.
I will document all of my progress in this repo's site.

# Specifications
I am using:
1. GLFW 3.3 (using [glad](https://glad.dav1d.de/))
2. [Microsoft Visual Studio 2022](https://visualstudio.microsoft.com/)

# Site
Visit this repo's site [here](https://gelastropod.github.io/openGL/). Note that this site will be ported to gatsby.js sometime before the end of this year, so there may be changes.

# Content
This repository will contain the entire Visual Studio project files for every chapter. See below.

# Chapters
This is my plan for learning openGL. Note that this is highly tentative and will most likely have edits and additions.  
**1\. Setting Up OpenGL Environment**

- **Project**: Set up an OpenGL window using GLFW, and ensure that the context is created.  
  - **Skills learned**: Window management, context creation, initializing OpenGL.  
  - **Goal**: Open a window with a background color.

**2\. Drawing Basic Shapes**

- **Project**: Draw a triangle and a square on the screen using vertex data and basic shaders.  
  - **Skills learned**: Vertex buffers, vertex array objects (VAO), shaders, and basic rendering pipeline.  
  - **Goal**: Understand how to send vertex data to the GPU and render basic shapes.

**3\. Moving Objects (Transformations)**

- **Project**: Add translation, rotation, and scaling to move and transform the triangle or square.  
  - **Skills learned**: Model, view, projection matrices, transformation matrices.  
  - **Goal**: Manipulate objects in 2D or 3D space using matrix operations.

**4\. Texturing**

- **Project**: Apply a 2D texture to the objects (e.g., a textured square).  
  - **Skills learned**: Texture coordinates, loading textures, texture sampling in shaders.  
  - **Goal**: Render textured objects.

**5\. Basic Lighting**

- **Project**: Implement simple Phong lighting with ambient, diffuse, and specular components.  
  - **Skills learned**: Normals, lighting calculations, per-vertex or per-pixel lighting in shaders.  
  - **Goal**: Create a scene with a light source that affects the object's appearance based on its position.

**6\. Camera Movement (View Matrix)**

- **Project**: Add a free-moving camera (using mouse and keyboard controls) to navigate the scene.  
  - **Skills learned**: View matrix, camera transformations, handling user input.  
  - **Goal**: Navigate through a 3D scene with the camera.

**7\. 3D Models**

- **Project**: Load and render 3D models from file formats like .obj or .fbx.  
  - **Skills learned**: Model loading (using libraries like Assimp), more advanced vertex data structures.  
  - **Goal**: Render complex 3D models instead of hardcoded shapes.

**8\. Advanced Lighting (Multiple Lights)**

- **Project**: Implement multiple light sources (point lights, spotlights, and directional lights).  
  - **Skills learned**: Light types, multiple lights, uniform buffer objects (UBOs) for light data.  
  - **Goal**: Handle different types of lights in the scene.

**9\. Shadows (Shadow Mapping)**

- **Project**: Implement shadow mapping to cast shadows from objects onto the scene.  
  - **Skills learned**: Depth buffer, shadow mapping, depth textures, light-space transformations.  
  - **Goal**: Create realistic shadows for dynamic lighting.

**10\. Normal Mapping**

- **Project**: Implement normal mapping to simulate more detailed surface textures without adding geometry.  
  - **Skills learned**: Tangent space, normal maps, lighting calculations based on normal maps.  
  - **Goal**: Add surface detail through texture-based normals.

**11\. Post-Processing Effects**

- **Project**: Implement post-processing effects like bloom, motion blur, and color correction.  
  - **Skills learned**: Framebuffer objects (FBOs), screen-space effects, render targets, and shaders.  
  - **Goal**: Apply post-processing to the rendered image for special effects.

**12\. Skybox**

- **Project**: Implement a skybox to render a background that simulates an infinite sky.  
  - **Skills learned**: Cube mapping, texture sampling, skyboxes.  
  - **Goal**: Create a dynamic environment with a textured skybox.

**13\. Deferred Rendering**

- **Project**: Implement deferred shading, where geometry and lighting passes are decoupled.  
  - **Skills learned**: G-buffer, deferred shading, multiple render targets (MRTs).  
  - **Goal**: Efficiently handle multiple lights in a complex scene.

**14\. SSAO (Screen Space Ambient Occlusion)**

- **Project**: Implement SSAO to add contact shadows and depth-based shading effects.  
  - **Skills learned**: Sampling in screen space, depth buffer processing.  
  - **Goal**: Add realism by calculating ambient occlusion.

**15\. Terrain Rendering**

- **Project**: Implement terrain rendering with heightmaps and level of detail (LOD) techniques.  
  - **Skills learned**: Heightmaps, tessellation, LOD.  
  - **Goal**: Render large-scale terrain with efficient detail management.

**16\. Advanced Ray Tracing (Compute Shader/RT)**

- **Project**: Implement ray tracing for reflections or refractions (potentially using compute shaders or RTX hardware if available).  
  - **Skills learned**: Ray tracing algorithms, acceleration structures (BVH), lighting models in ray tracing.  
  - **Goal**: Handle complex lighting, reflections, and realistic material interactions.

**17\. Physics Simulation**

- **Project**: Add physics-based interactions to objects in the scene (e.g., collisions, rigid-body dynamics).  
  - **Skills learned**: Physics engine integration (Bullet or custom physics), physics simulations.  
  - **Goal**: Create dynamic, interactive scenes with physics-based animations.

**18\. PBR (Physically-Based Rendering)**

- **Project**: Implement PBR to create more realistic materials and lighting based on physical properties.  
  - **Skills learned**: BRDFs (Bidirectional Reflectance Distribution Functions), image-based lighting (IBL), PBR texture maps (albedo, roughness, metallic, etc.).  
  - **Goal**: Achieve more realistic rendering with physically-based materials and lighting.

**19\. Global Illumination (Path Tracing)**

- **Project**: Implement global illumination using path tracing to simulate realistic light bounces.  
  - **Skills learned**: Path tracing, Monte Carlo integration, light transport algorithms.  
  - **Goal**: Achieve realistic lighting effects with multiple light bounces and indirect lighting.

