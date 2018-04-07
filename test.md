# NXT, standalone part

NXT is an unoriginal name for Chromium’s investigation and prototyping of a NeXT generation 
graphics API for the Web. 
This repository contains a native library implementing NXT on multiple backends, as well 
as some code generators used for the integration in Chromium. NXT is not an official Google product.

NXT currently has the following features:

- Command buffers, graphics and compute pipelines
- Textures, samplers, vertex / index / uniform / storage buffers.
- Descriptor sets (called bind groups) and push constants
- SPIRV for the shading language
- Validation