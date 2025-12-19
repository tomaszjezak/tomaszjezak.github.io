---
layout: page
title: Academic Question Answering
description: Dense retrieval with Supervised Contrastive Learning for the KDD Cup 2024
img: assets/img/aqa.png
importance: 4
category: research
github: https://github.com/tomaszjezak/KDD_AQA
---

## Overview

Developed a **dense retrieval model** for Academic Question Answering utilizing **Supervised Contrastive (SupCon) loss** — the first application of SupCon to text retrieval.

## Key Contributions

- **Novel Loss Function**: First application of Supervised Contrastive loss to text retrieval tasks
- **Hard Negative Mining**: Incorporated hard negative mining during training to enhance model robustness
- **Efficient Retrieval**: Implemented HNSW (Hierarchical Navigable Small World) graphs for efficient nearest-neighbor retrieval
- **Competition Results**: Achieved leaderboard score of **0.119 (35th place)** in the KDD Cup 2024

## Technical Details

The model leverages dense embeddings to match academic questions with relevant papers and answers. By using SupCon loss, the model learns to pull similar question-answer pairs together in the embedding space while pushing dissimilar pairs apart.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <p class="text-center">
            <a href="https://drive.google.com/file/d/1ZrXaqRreqks5QQcP6_j6YSXt2dtIq9YQ/view?usp=sharing" class="btn btn-primary" target="_blank">📄 Read Paper</a>
            <a href="https://www.youtube.com/watch?v=b966wf8bGmU" class="btn btn-outline-primary" target="_blank">🎥 Watch Video</a>
            <a href="https://github.com/tomaszjezak/KDD_AQA" class="btn btn-outline-primary" target="_blank">💻 View Code</a>
        </p>
    </div>
</div>

