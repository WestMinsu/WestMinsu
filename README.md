<h1 align="center">Minsu Seo</h1>

<p align="center">
  <b>Rendering Programmer</b><br>
  DirectX 12 · Vulkan · C++ · Real-Time Rendering
</p>

<p align="center">
  <a href="https://github.com/WestMinsu/WestEngine">
    <img src="https://raw.githubusercontent.com/WestMinsu/WestEngine/master/images/bistro.png" alt="WestEngine Bistro scene" width="820">
  </a>
</p>

## Main Project: WestEngine

**WestEngine** is my main rendering project: a DirectX 12 / Vulkan dual-backend real-time rendering engine built around a shared RHI.

- **Unified RHI:** DX12 and Vulkan backends run through the same renderer-facing interfaces.
- **Bindless Resource Model:** Resources are accessed by index through a global descriptor model.
- **Render Graph:** Pass/resource dependencies drive barriers, transitions, and transient resource aliasing.
- **GPU-Driven Rendering:** Compute culling feeds indirect draw submission.
- **Deferred PBR Pipeline:** GBuffer, Shadow, SSAO, Deferred Lighting, IBL, Bokeh DOF, Tone Mapping, and color grading.
- **Shader Pipeline:** Slang generates DXIL and SPIR-V from shared shader sources.

Measured on the Amazon Lumberyard Bistro scene: **2.84M triangles**, **DX12 272.3 FPS**, **Vulkan 279.4 FPS** on RTX 3060.

<p>
  <a href="https://github.com/WestMinsu/WestEngine"><b>WestEngine Repository</b></a>
  ·
  <a href="https://docs.google.com/presentation/d/1tfTBp06uEOTYr-qzJ8vhQBhm_r3lKSVhpbtk1gBXgyM/edit?usp=sharing"><b>Supplementary Slides</b></a>
  ·
  <a href="https://westminsu.github.io/Portfolio/"><b>Portfolio Website</b></a>
</p>

## Focus

I am interested in rendering systems close to the graphics API layer, especially GPU resource binding, frame graph scheduling, GPU-driven submission, and real-time lighting/post-processing pipelines.
