# 🚀 HunyuanVideo-Foley

<div align="center">

<img src="assets/logo.png" alt="HunyuanVideo-Foley Logo" width="400">

<h4>Portable Version</h4>

<h4>Multimodal Diffusion with Representation Alignment for High-Fidelity Foley Audio Generation</h4>

<p align="center">
  <strong>Professional-grade AI sound effect generation for video content creators</strong>
</p>
</div>


![HunyuanVideo-Foley](img/HunyuanVideoFoley.jpg)

[![Release](https://img.shields.io/github/release/LeeAeron/HunyuanVideo-Foley.svg)](https://github.com/LeeAeron/HunyuanVideo-Foley/releases/latest)


## ✨ **Key Highlights**

<table align="center" style="border: none; margin: 20px 0;">
<tr>
<td align="center" width="33%">
  
🎭 **Multi-scenario Sync**  
High-quality audio synchronized with complex video scenes

</td>
<td align="center" width="33%">
  
🧠 **Multi-modal Balance**  
Perfect harmony between visual and textual information

</td>
<td align="center" width="33%">
  
🎵 **48kHz Hi-Fi Output**  
Professional-grade audio generation with crystal clarity

</td>
</tr>
</table>

</div>


## 🎯 **Core Highlights**

<div style="display: grid; grid-template-columns: 1fr; gap: 15px; margin: 20px 0;">

<div style="border-left: 4px solid #4CAF50; padding: 15px; background: #f8f9fa; border-radius: 8px; color: #333;">
  
**🎬 Multi-scenario Audio-Visual Synchronization**  
Supports generating high-quality audio that is synchronized and semantically aligned with complex video scenes, enhancing realism and immersive experience for film/TV and gaming applications.

</div>

<div style="border-left: 4px solid #2196F3; padding: 15px; background: #f8f9fa; border-radius: 8px; color: #333;">
  
**⚖️ Multi-modal Semantic Balance**  
Intelligently balances visual and textual information analysis, comprehensively orchestrates sound effect elements, avoids one-sided generation, and meets personalized dubbing requirements.

</div>

<div style="border-left: 4px solid #FF9800; padding: 15px; background: #f8f9fa; border-radius: 8px; color: #333;">
  
**🎵 High-fidelity Audio Output**  
Self-developed 48kHz audio VAE perfectly reconstructs sound effects, music, and vocals, achieving professional-grade audio generation quality.

</div>
</div>


## ⚙️ Installation

**🔧 Portable Version Specs:**
- **CUDA**: 12.8
- **Python**: 3.12 
- **OS**: Windows 10/11
- **VRAM**: 20GB for XXL model (or 8GB with offload mode), 16GB for XL model (or 6GB+ with offload mode)


### 🖥️ Windows Installation

This project provided with only *.bat installer/starter file, that will download and install all components and build fully portable HunyuanVideo-Foley.

➤ Please Note:
    - I'm supporting only nVidia 16xx and RTX20xx-50xx GPUs. Work with GTX10xx is not guarantied, sorry, too old GPU.
    - This installer is intended for those running Windows 10 or higher. 
    - Application functionality for systems running Windows 7 or lower is not guaranteed.

- Download the F5-TTSx .bat installer for Windows in [Releases](https://github.com/LeeAeron/HunyuanVideo-Foley/releases).
- Place the BAT-file in any folder in the root of any partition with a short Latin name without spaces or special characters and run it.
- Select INSTALL (5) entry .bat file will download, unpack and configure all needed environment.
- The batch file downloads portable Git and Microconda, creates a portable venv, installs last official stable Torch with Cuda 12.8, downloads models, and then deletes part of the downloaded cache. 
After installation, the batch file will automatically launch the browser and begin downloading the google--siglip2-base-patch16-512 and laion--larger_clap_general models to the cache folder. 
Please be patient and wait for the shell to start (monitor in the console).
- After installation use one of 4 launch modes (1-4) in the *.BAT MENU: XXL/XL model in two modes - without and with Offload. OFFLOAD uses VRAM and RAM, so if you have 32GB+ of RAM, use OFFLOAD.


## 💻 **Usage**

### 📊 **Model Specifications**

| Model               | Checkpoint                  | VRAM (Normal) | VRAM (Offload) |
|---------------------|-----------------------------|---------------|----------------|
| **XXL** *(Default)* | `hunyuanvideo_foley.pth`    | 20GB          | 12GB           |
| **XL**              | `hunyuanvideo_foley_xl.pth` | 16GB          | 8GB            |


## 📺 Credits

<div align="center" style="margin: 30px 0;">
<p style="color: #666; margin-top: 15px; font-size: 14px;">
  
© 2025 Tencent Hunyuan. All rights reserved. | Made with ❤️ for the AI community
© 2026 LeeAeron, Portable version.

</p>
</div>
