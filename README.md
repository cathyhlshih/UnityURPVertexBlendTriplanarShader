# Unity URP Vertex Blend Triplanar Shader

<img src="/UnityURPVertexBlendTriplanarShader/Images/CathyShih_StylizedSandstoneCliff_Demo.png" alt="CathyShih_StylizedSandstoneCliff_Demo" style="width:600px;"/>

This shader uses triplanar mapping, blending multiple textures using the mesh's vertex colors. It blensd between textures with height maps to create customizable transitions and realistic terrain representation. It is suited for those who want to use meshes for terrains instead of Unity's terrains. 

* Unity 2022.3.16f1LTS
* URP 14.0.9
* Shader Graph 14.0.9

The shader uses the same mask textures as in Unity's Terrain engine. 

Currently, the shader uses the R, G, and B channels to blend three textures. An additional Alpha channel can be incorporated for a fourth texture.

A procedurally generated cliff FBX file and textures are attached to this Repo as a demo. The cliff model was generated in Blender using its A.N.T Landscape addon, and the splat map was generated based on slope angles then applied to vertex colors.

<img src="/UnityURPVertexBlendTriplanarShader/Images/CathyShih_StylizedSandstoneCliff_VertexColorDemo.png" alt="CathyShih_StylizedSandstoneCliff_VertexColorDemo" style="width:600px;"/>

Here is another example where you can use Unity's Polybrush to paint vertex colors directly onto meshes with this shader.

<img src="/UnityURPVertexBlendTriplanarShader/Images/CathyShih_RealisticForestCliff_VertexPaintDemo.gif" alt="CathyShih_RealisticForestCliff_VertexPaintDemo" style="width:600px;"/>

<img src="/UnityURPVertexBlendTriplanarShader/Images/CathyShih_RealisticForestCliff_VertexPaintedDemo.png" alt="CathyShih_RealisticForestCliff_VertexPaintedDemo" style="width:600px;"/>
