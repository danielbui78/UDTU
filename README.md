# Unofficial DazToRuntime
Unofficial updates to DazToUnity Bridge.

BRANCH: unity-builtin-support

Removes HDRP dependencies from DTU scripts and adds custom IrayUberShaders for Unity Built-In render pipeline (based on Unity Standard Shader source code).  My goal is to keep these custom shaders as compatible as possible with the original DazToUnity Bridge HDRP IrayUber shaders, so that they are nearly plug-in replacements for the original shaders.  Currently, they do need some parameter settings and shader Keyword names which diverge from the original shaders, but hopefully the shader code can modified for better compatibility in the future.

Note: all Built-In shader files currently share the same exact code.  Will differentiate in the future.

Currently supports:
- Diffuse Color and Map
- Normal Strength and Map
- Alpha Cutoff, Cutout Opacity and Map
- Smoothness
- Metallicity (Metallic Weight)
