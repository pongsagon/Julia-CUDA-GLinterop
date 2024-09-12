
![julia](https://github.com/user-attachments/assets/dc2c089b-eff8-4fb5-85a1-ffde85dc4302)

# Julia-CUDA-GLinterop
Using CUDA to compute Julia fractal, drawing using OpenGL, use win32 for touch input <br />
Rendering at 4K, each pixel compute using 1200 iterations, running at 10-15fps on RTX4090 <br />
This version use CUDA/OpenGL interop to draw the result as a full screen texture quad. I am also using shader.h and some other gl code snippets  from learnopengl.com by Joey de Vries to init some shader codes.

## User guides
The code uses touch input.  You can add glfw code for keyboard and mouse inputs <br />
move one finger to pan <br />
move two fingers up and down to zoom <br />
move three fingers to change seed <br/>


## Compiling using MSVC 2022 (WIP)
Library used
- GLFW
- glew
- stb_image
- GLM please put it in the includes folder. get it here https://github.com/g-truc/glm


## Acknowledgement
The Julia CUDA code is based on the code from "CUDA by examples" book by Jason Sanders and Edward Kandrot.<br/>
Shader.h is from learnopengl.com by Joey de Vries
