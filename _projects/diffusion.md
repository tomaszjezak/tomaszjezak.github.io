---
layout: page
title: Image Diffusion Fine-Tuning
description: Fine-tuning Stable Diffusion for Fan Art generation
img: assets/img/diffusion.png
importance: 2
category: research
---

## Overview

Fine-tuned **Stable Diffusion** and **SDXL** with custom datasets to synthesize fan art with consistent style and character preservation.

## Key Contributions

- **Custom Dataset Curation**: Built specialized datasets for fan art fine-tuning
- **DreamBooth Innovation**: Hacked the DreamBooth technique to store **environments across diffusions** instead of objects, enabling more creative and contextual image generation
- **Multi-Model Approach**: Compared and evaluated both Stable Diffusion 1.5 and SDXL architectures

## Technical Approach

Traditional DreamBooth focuses on learning specific objects or subjects. Our modification allows the model to capture and reproduce entire environments and artistic styles, making it particularly effective for fan art that requires consistent world-building aesthetics.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <p class="text-center">
            <a href="https://ucladeepvision.github.io/CS188-Projects-2024Winter/2024/03/20/team39-Finetuning-Stable-Diffusion.html" class="btn btn-primary" target="_blank">📄 Read Paper</a>
        </p>
    </div>
</div>

