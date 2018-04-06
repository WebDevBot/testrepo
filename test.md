# NXT, standalone part

NXT is an unoriginal name for Chromium’s investigation and prototyping of a NeXT generation graphics API for the Web. This repository contains a native library implementing NXT on multiple backends, as well as some code generators used for the integration in Chromium. NXT is not an official Google product.

We focused on efforts on two axis:

- An investigation of the constraints coming from the Web and in particular portability, for which we looked at the intersection of the designs of D3D12, Metal, Vulkan, OpenGL and D3D11. See links to some of our investigations below.
- A prototype API inspired by all of D3D12, Metal and Vulkan, but none in particular. The API works on two backends: OpenGL and Metal and is usable from native code (think WebAssembly) and from Javascript inside of Chrome. Our focus was not to have a complete API but to show the breadth of potential usage.

We’re making our investigation and prototype public to provide another example for the upcoming discussion in the “GPU for the Web” W3C community group.

NXT currently has the following features:

- Command buffers, graphics and compute pipelines
- Textures, samplers, vertex / index / uniform / storage buffers.
- Descriptor sets (called bind groups) and push constants
- SPIRV for the shading language
- Validation
