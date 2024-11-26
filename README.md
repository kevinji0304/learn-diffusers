# Learn Diffusers

My personal learning path and notes for understanding Hugging Face's Diffusers library - a powerful toolkit for working with diffusion models in deep learning.

## Environment Setup

1. Clone this repository:

```bash
git clone https://github.com/kevinji0304/learn-diffusers.git
cd learn-diffusers
```

2. Create a conda environment:

```bash
conda create -n diffusers python=3.10
conda activate diffusers
```

3. Install dependencies:

```bash
conda install pytorch torchvision -c pytorch
pip install diffusers transformers accelerate
```

4. If you have CUDA enabled, install the CUDA version of PyTorch:

```bash
conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch -c nvidia
```

## Learning Progress

This repository contains my journey through learning diffusion models with the Diffusers library. Each example includes my notes and insights as I explore different aspects of the library.

### Contents

- Basic usage examples
- Implementation studies
- Experiment results
- Personal observations and learnings
