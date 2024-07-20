# Rotating-Cube

Overview

This project demonstrates a simple OpenGL application that renders a rotating cube. It serves as a basic introduction to 3D graphics using OpenGL and can be a foundation for more complex graphical projects.
Features

    Renders a 3D cube.
    Applies basic transformations to rotate the cube.
    Uses the OpenGL, GLEW, and GLFW libraries.

Requirements

    Operating System: Linux (Fedora preferred)
    Compiler: g++
    Libraries:
        OpenGL
        GLEW
        GLFW

Installation
Prerequisites

Ensure you have the following packages installed:

    GLFW: sudo dnf install glfw-devel
    GLEW: sudo dnf install glew-devel
    OpenGL: Typically included in Mesa or similar packages.

Clone the Repository

bash

git clone https://github.com/username/repository.git
cd repository

Build the Project

    Navigate to the project directory:

    bash

cd /path/to/your/project

Create a build directory:

bash

mkdir build
cd build

Compile the project:

bash

    g++ -g ../main.cpp -o RotatingCube -lGL -lGLU -lGLEW -lglfw -I/usr/include -I/usr/include/GL -I/usr/include/GLFW

Run the Project

Execute the compiled binary:

bash

./RotatingCube

Usage

When you run the application, you should see a window displaying a rotating 3D cube. You can modify the cube's rotation and other parameters in the main.cpp file to experiment with different effects.
Troubleshooting

    Compilation Errors: Ensure all required libraries are installed and paths are correctly set.
    Runtime Errors: Check for missing dependencies and ensure that OpenGL is correctly installed on your system.

Contribution

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.


For any questions or issues, please contact Aryan Bhattarai.
