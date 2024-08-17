# Vulkan Template for C++

Basic template for the Vulkan C++ development environment. I'm saving this here just in case I need to set this up again on my computer.

### Prerequisites

visit [the official vulkan tutorial site](https://vulkan-tutorial.com/Development_environment#page_Linux) for an actual guide.

You're first going to want to install all of these Vulkan packages and additional libraries.

Arch:
```sh
sudo pacman -S vulkan-devel glfw-wayland glm shaderc
```

Fedora:
```sh
sudo dnf install vulkan-tools vulkan-loader-devel vulkan-validation-layers-devel glfw-devel glm-devel glslc
```

### Getting Started

Create a directory for your project and copy the main.cpp and Makefiles and you're all set.
