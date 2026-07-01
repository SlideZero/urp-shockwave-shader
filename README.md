<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/9bc31ee9-e392-41f7-bf34-655a50fa2fa3">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/93b65b4f-8523-41d4-9bd0-edf0c1c7972c">
    <img src="https://github.com/user-attachments/assets/93b65b4f-8523-41d4-9bd0-edf0c1c7972c" width="200"/>
  </picture>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Unity-2020.1.2-lightgrey"/> <img src="https://img.shields.io/badge/Template-URP-green"/> <img src="https://img.shields.io/badge/Feature-Shader_Graph-blue"/> <img src="https://img.shields.io/badge/Status-Experimental-red"/>
</p>

<h2 align="center">Shockwave Shader</h2>

Unity shockwave visual effect. This is an experimental project made as a hobby and derived from the [original project](https://github.com/SlideZero/shockwave-shader) originally aimed at the <em>built-in render pipeline.</em>

This project makes use of the URP (<em>Universal Render Pipeline</em>) template.

## Key Concepts:

The basic settings are based on these two concepts:
- [Camera Stacking](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@7.2/manual/camera-stacking.html)
- [Opaque Texture](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@7.1/manual/universalrp-asset.html)

The <b>Opaque Texture</b> concept is based on the [GrabPass](https://docs.unity3d.com/Manual/SL-GrabPass.html) ShaderLab command.

## Overview:

<img src="https://zesdev-resources.s3.amazonaws.com/urp-shockwave-shader.gif"/>
