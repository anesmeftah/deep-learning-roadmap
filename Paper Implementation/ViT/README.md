# Vision Transformer (ViT) from Scratch

Implementation of **"An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"**  
([Dosovitskiy et al., 2020](https://arxiv.org/abs/2010.11929)) in PyTorch.

---

## 📌 Project Overview
This project is a clean, from-scratch implementation of the **Vision Transformer (ViT)** architecture.  
It demonstrates how transformers—originally designed for NLP—can be applied to image classification by splitting images into fixed-size patches and processing them as sequences.

---

## 🔨 Features
- **Patch Embeddings**: Images are split into 16×16 patches and projected into embedding vectors.
- **Class Token**: Learnable token prepended to embeddings for classification.
- **Positional Encoding**: Added to preserve spatial information of patches.
- **Transformer Encoder Blocks**: Multi-head self-attention + feed-forward layers.
- **Training Pipeline**: Full loop with optimizer, loss function, and accuracy tracking.
- **Results Visualization**: Loss and accuracy curves plotted across epochs.

---

## 🚀 Next Steps
- Add advanced data augmentations (RandAugment, Mixup, CutMix).  
- Experiment with fine-tuning pretrained ViTs.  
- Compare systematically with CNN baselines.  
- Visualize attention maps for interpretability.  

---
