# 📜 Diffusion Research Timeline  

🚀 **A chronological timeline of key research papers on diffusion models**, documenting their evolution and linking to their arXiv sources. This repo provides **summaries, breakthroughs, and the impact** of each paper to help students, researchers, and AI enthusiasts understand how diffusion models have developed over time.  

📑 Citation counts are as of February 11, 2025

---

## 📌 **Table of Contents**
- [Foundational Papers (2015–2019)](#1)
- [Core Diffusion Model Developments (2020–2021)](#2)
- [Transformers & Diffusion Models (2020–2023)](#3)
- [Diffusion Beyond Images: Video & Audio (2021–2022)](#4)
- [Latent Diffusion & Scaling (2022–2023)](#5)
- [Text-to-Image & Multimodal Diffusion (2021–2022)](#6)
- [Improving Diffusion Efficiency & Sampling (2022–2024)](#7)

---

## Foundational Papers (2015–2019)   <a id='1'></a>
> **Laying the mathematical groundwork for diffusion models.**  

- **[Deep Unsupervised Learning Using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585)** – *Sohl-Dickstein et al., 2015*  
  🏗️ First proposed diffusion models as a **thermodynamic process**, introducing the forward (noise addition) and reverse (denoising) diffusion process. 📑 Cited 7,007 times since 2015 

- **[Generative Modeling by Estimating Gradients of the Data Distribution](https://arxiv.org/abs/1907.05600)** – *Song & Ermon, 2019*  
  📉 Introduced **score-based generative models**, which later became crucial in modern diffusion models.
  📑 Cited 3,842 times since 2019

---

## Core Diffusion Model Developments (2020–2021)   <a id='2'></a>
> **Defining the structure of diffusion models & making them competitive with GANs.**  

- **[Denoising Diffusion Probabilistic Models (DDPM)](https://arxiv.org/abs/2006.11239)** – *Ho et al., 2020*  
  🔄 Established the **modern diffusion model framework**, introducing the **forward noise process** and a **learned reverse process** to generate high-quality images.  📑 Cited 17,651 times since 2020

- **[Denoising Diffusion Implicit Models (DDIM)](https://arxiv.org/abs/2010.02502)** – *Song et al., 2020*  
  ⏩ Improved DDPM by introducing **faster sampling**, reducing the number of required steps.  📑 Cited 6,629 times since 2020

- **[Improved Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2102.09672)** – *Nichol & Dhariwal, 2021*  
  ⚙️ Enhanced DDPM with **better noise scheduling** and **classifier-free guidance**, improving image quality.  📑 Cited 3,614 times since 2021

- **[Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233)** – *Dhariwal & Nichol, 2021*  
  🎯 Demonstrated that **diffusion models outperform GANs** in high-quality image generation.  📑 Cited 7,477 times since 2021

---

## Transformers & Diffusion Models (2020–2023)   <a id='3'></a>
> **Exploring transformer architectures for diffusion models.**  

- **[An Image Is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)** – *Dosovitskiy, 2020*  
  🖼️ Introduced **Vision Transformers (ViTs)**, influencing hybrid architectures that combine transformers with diffusion models.  📑 Cited 54,671 times since 2020

- **[Scalable Diffusion Models with Transformers](https://arxiv.org/abs/2212.09748)** – *Peebles & Xie, 2023*  
  🏗️ Proposed **transformer-based diffusion models**, improving scalability and efficiency.  📑 Cited 1,599 times since 2023

---

## Diffusion Beyond Images: Video & Audio (2021–2022)   <a id='4'></a>
> **Extending diffusion models beyond static images.**  

- **[Video Diffusion Models](https://arxiv.org/abs/2204.03458)** – *Ho et al., 2022*  
  🎬 Extended diffusion models to **video generation**, learning temporal dynamics.  📑 Cited 1,451 times since 2022

- **[DiffWave: A Versatile Diffusion Model for Audio Synthesis](https://arxiv.org/abs/2009.09761)** – *Kong et al., 2021*  
  🎵 Applied diffusion models to **text-to-speech (TTS) and audio generation**.  📑 Cited 1,471 times since 2021

---

## Latent Diffusion & Scaling (2022–2023)   <a id='5'></a>
> **Optimizing diffusion models for high-resolution image generation.**  

- **[High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)** – *Rombach et al., 2022*  
  🖼️ Introduced **Latent Diffusion Models (LDM)**, moving diffusion to **latent space**, reducing computational costs.  📑 Cited 15,267 times since 2022

- **[SDXL: Improving Latent Diffusion Models for High-Resolution Image Synthesis](https://arxiv.org/abs/2307.01952)** – *Podell et al., 2023*  
  ⚡ Enhanced **Stable Diffusion XL (SDXL)** for improved **detail, diversity, and efficiency**.  📑 Cited 1,596 times since 2023

---

## Text-to-Image & Multimodal Diffusion (2021–2022)   <a id='6'></a>
> **Applying diffusion models to multimodal tasks.**  

- **[Zero-Shot Text-to-Image Generation](https://arxiv.org/abs/2102.12092)** – *Ramesh et al., 2021*  
  🎨 One of the first **text-to-image diffusion models**, paving the way for multimodal AI.  📑 Cited 6,396 times since 2021

- **[Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://arxiv.org/abs/2205.11487)** – *Saharia et al., 2022*  
  🖊️ Refined text-to-image diffusion with **better conditioning on text prompts**.  📑 Cited 6,396 times since 2022

---

## Improving Diffusion Efficiency & Sampling (2022–2024)  <a id='7'></a>
> **Enhancing speed, stability, and computational efficiency.**  

- **[Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/abs/2206.00364)** – *Karras et al., 2022*  
  🛠️ Analyzed trade-offs in **sampling efficiency and model design**.  📑 Cited 6,396 times since 2015
 

- **[Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](https://openreview.net/forum?id=FPnUhsQJ5B)** – *Esser et al., 2024*  
  🚀 Improved **stability and scalability** of diffusion models.  📑 Cited 6,396 times since 2015

---

## 📌 How to Use This Repository  
- 🏛️ **Read the Papers**: Click the links to access each paper on **arXiv**.  
- 📖 **Learn the Evolution**: Follow the timeline to understand how diffusion models developed.  
- 🔬 **Stay Updated**: Contributions & new research additions are welcome!  

---

### ⭐ **Contribute**
Want to add new papers or improve descriptions? Open an **issue** or submit a **pull request**!  

📢 **If you found this useful, give it a star ⭐ and share it!**  

