# OpenGL Environment
An easy to manage development environment for OpenGL projects using CMake.

Parts of `Source/OpenGLEnvironment.cpp` are from [LearnOpenGL](https://learnopengl.com/Getting-started/Hello-Window).

## Setup
### Windows
With the prerequisites you can use `GenerateVS2019.bat` to generate the Visual Studio 2019 Solution that will be put in `Generated`. The dependencies can be pulled or initialized using `SetupDependencies.bat`. `LaunchVS2019.bat` can be used to launch the VS Solution. The binaries and associated build files are put in `Binaries`.

### Prerequisites
Name | Description
------------ | -------------
[CMake](https://cmake.org/) | 3.7.0+
[Python](https://www.python.org/) | Python 2.8+

## Dependencies
Name | Description | License
------------ | ------------- | -------------
[GLFW](https://github.com/glfw/glfw) | Multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input | [ZLIB](https://github.com/glfw/glfw/blob/master/LICENSE.md)
[GLM](https://github.com/g-truc/glm) | OpenGL math library | [MIT](https://github.com/g-truc/glm/blob/master/manual.md#section0)
[GLAD](https://github.com/Dav1dde/glad) | Multi-Language GL Loader-Generator | [MIT](https://github.com/Dav1dde/glad/blob/master/LICENSE)

## Bugs, issues and suggestions
Feel free to open issues in case you encounter bugs, want to make suggestions or need help.
