<p align="center">
<img src="https://github.com/SlideZero/icons-logos/blob/main/Unity/unity-tab-square-white.png" width="140"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Unity-2020.1.2-lightgrey"/> <img src="https://img.shields.io/badge/Template-URP-brightgreen"/> <img src="https://img.shields.io/badge/Feature-Shader_Graph-blue"/> <img src="https://img.shields.io/badge/Status-Experimental-red"/>
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

<img src="https://zesdev-resources.s3.us-east-1.amazonaws.com/urp-shockwave-shader.gif?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAkaCXVzLWVhc3QtMiJIMEYCIQC%2Fhqsg2lrx6KUJZ9nPM26ehhBT00cLJBD9SGW2TnnspgIhAOUTRTjTxXcc%2Fc2BvH9DqUrijKu82Gu4fdvyzhYH4fVZKvYCCFIQABoMODM3ODMyNzczNTAxIgzCdtTesdxISFRNDqAq0wIHu%2F6BWrqtiFNoYgAgTXTE%2BvJdvJp5HPZV7S1cCf5mCJxJe8TKqkuJvqKyjWCmQwipxE41GoKzWkvksYlkeUYIqJbIhsImeFn0UOgbPtBECFk%2FG%2BRp0ZeZDdKo6C%2FjYIBCmWtSFMMBfIIM1b%2BNKlLlABMUXgJxOF3TcVkNY9v0wveeVoYifbc5gliVboyvIF2iG1DrgFLirX%2BeVwTdvKSA5GhfREPpPph86i8WSqV0zlGsxZXgk7vcgwoo2nym4pn6t%2F1GXlhs%2BY0RUBl8A%2FDrSF6xnC1hQSLiD9U8FguGjJpMoHKZ%2Fr5JNKf%2BwodxDzUUJ46hw57V%2BRxFz54k9lizd0IXmwXgQVO9qWJFS2ZDCS8jisXYtsa1Rx6nfXw0j%2FSrCXkXcMiQPklYUUMVXRWTEX6ubkW%2F66VRjW6it2tf7l55hAsM9SuH96p7nYVbsFzELa0wiaXQiQY6sgLEupIu1TeZkMX39lGrS1YLVGIrDSZCkK%2Bqqj0tG0hWdhZRtzG2mDS88oCX9z7wHkZ%2FtcrBSfZqztWeVUTOkEvagZwY68PdIgiFsa6ew52LVs1RSRwmcu3%2FxJxkXIFQH1C6HKNioaUrWgh7ovhNfsSNLzw7Q5E5M2avtYYyhKQeUVEjwCVQ6lg1Ihi4Wyf4g3y0FobsLeW1AMf6Mub6Z2NqzQov3BgyN2%2BAisw%2FZ8majKpX5qst%2BfMwMrRsapB445dr3%2B%2FpGvj8Pan8PquuOUNoO57imGvfIpCnUrx36n%2BBx9DldvjL6axXZjgRq3PNiVZKcvh9LsStvsyMgTfvX1LvqX%2Br%2BJTwy8X8vlJgbak6Ohn81E0wgKbOooOzlE0rOGhBsFJGLEQtrsHz%2BWS9gX0wi9A%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210905T012520Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIA4GEVZR56YELD2UPI%2F20210905%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=0f898ca71a9d734c2a5824a020362bfe6cc21feb6cfa7f136c55905b36e62ab9"/>
