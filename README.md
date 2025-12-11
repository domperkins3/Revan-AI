<div align="center">

# Revan AI

**Android Stable Diffusion image generation**  
_Fork of Local Dream with custom branding and future Google Pixel focus_

</div>

---

## About Revan AI

**Revan AI** is a personal, experimental fork of  
[Local Dream by xororz](https://github.com/xororz/local-dream).

Goals of this fork:

- 💠 Custom branding as **Revan AI**
- 📱 Experiments with **Google Pixel–focused builds**
- 🧱 Keep as much of the original Local Dream features and UX as possible

> This project is **not** an official release of Local Dream.  
> Almost all of the core magic comes from the original project – huge credit to **xororz** and contributors.

---

## ✨ Features (inherited from Local Dream)

Most features are identical to upstream Local Dream:

- 🎨 **txt2img** – generate images from text prompts  
- 🖼️ **img2img** – transform existing images  
- 🎭 **Inpainting** – modify selected regions of an image  
- 🧩 **Custom models** – import your own SD 1.5 models for CPU/GPU or quantized NPU  
- 🧬 **LoRA support** – LoRA weights for CPU models  
- 🔤 **Prompt weighting** – `(masterpiece:1.4), (detailed:1.2)` style prompts  
- 🧠 **Textual inversion / embeddings** – `.safetensors` embeddings (EasyNegative, etc.)  
- ⬆️ **Upscaling** – Real-ESRGAN / UltraSharp upscalers  

Future work in this repo will aim at **Pixel hardware** and tighter **Revan AI** integration.

---

## 🧱 Project Status

Right now, this fork is mainly:

- ✅ Rebranded to **Revan AI**
- ✅ Tracking upstream Local Dream features
- 🧪 Preparing for **Pixel-only builds** and future **Pixel NPU backends**

If you want a mature, battle-tested version, you should still use the original Local Dream for now. Revan AI is where the experimental stuff will happen.

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone --recursive https://github.com/domperkins3/Revan-AI.git
cd Revan-AI
