# OpenGLTemplate
C++ OpenGL template with GLFW, GLAD, and CMake

| Operating SYS | Build |
|---------------|-------|
|Windows        |❔     |
|MacOS          |✅     |
|Linux          |❔     |

This program was authored on MacOS

## Goal
I wanted to make a quick and simple OpenGL dev environment template with little to no prior setup required.

## Prerequisites
- CMake version 3.19 or higher

## Info
- Requires CMake 3.19 for Macos M1 Support
- Comes with GLAD configured with the gl 4.1 API and compatibility profile
- GLFW and glm are submodules (use --recursive when cloning)

## Usage
1. Clone the repo **recursively** `git clone --recursive https://github.com/prodskimaya/OpenGLTemplate.git`
2. Cd into the repo and create a build folder, and then cd into that: `cd OpenGLTemplate`, `mkdir build`, & `cd build`
3. Run CMake in the build folder and compile the application using your build system of choice (in this case, make): `cmake ..` & `make`

## Credit
- Thanks to [LearnOpenGL](https://learnopengl.com) and [TheCherno](https://github.com/TheCherno) for their OpenGL learning resources.
- Thanks to [cliutils on gitlab](https://cliutils.gitlab.io/) for their [Introduction to Modern CMake gitbook](https://cliutils.gitlab.io/modern-cmake/).
