# fxdis-d3d1x
Automatically exported from code.google.com/p/fxdis-d3d1x

FXDIS is a simple Win32 command line tool written in C/C++ with the MIT license forked from the relatively new (and experimental) Mesa "D3D1X" module. This tool can disassemble Shader Model 4/5 binary shaders created by Microsoft's DirectX v10/11 shader compiler. The decoded shader program can be easily accessed, potentially enabling the straightforward creation of low-level automated shader translation tools (for example, from compiled shader model 4/5 programs to GLSL) and simplifying the creation of a D3D 11 to OpenGL translation layer.

The tool can be compiled with Microsoft Visual Studio 2008/2010. This tool is completely standalone, i.e. it does not depend or include any headers from the Windows or DirectX SDK, and it does not rely on the Direct3D/D3DX runtime to function.

This tool surely has bugs, but after a few fixes it appears to be working surprisingly well. A huge thanks to Luca Barbieri (luca@luca-barbieri.com), the original author (and copyright holder) of this module. Also thanks to llyzs.vic@gmail.com for submitting his fixes (currently only checked into SVN).



