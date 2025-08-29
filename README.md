# Image classification with ViT & Robust Zero-Shot CLIP
### Q1 — Plant Disease Classification with ViT & Inception-V3  
Implemented and trained a **Vision Transformer (ViT)** for classifying tomato leaf diseases, and compared its performance with a **CNN baseline (Inception-V3)**.  
The pipeline included preprocessing, data augmentation, training visualization (loss/accuracy curves), and evaluation via confusion matrices.  

- **Results:**  
  - ViT: ≈ 95.4% accuracy (728k params)  
  - Inception-V3: ≈ 85% accuracy (21.8M params)  
  - ViT achieved higher accuracy with far fewer parameters, showing its efficiency for this task.

### Q2 — Robust Zero-Shot Classification with CLIP  
Evaluated **CLIP** on CIFAR-10 in a **zero-shot classification** setting, then tested robustness against adversarial attacks (**PGD, FGSM**).  
Applied defense methods including **LoRA fine-tuning**, **TeCoA adversarial training**, and **visual prompting** to improve adversarial resilience.  

- **Results:**  
  - Base CLIP: clean ≈ 87.8%, adv ≈ 54.9%  
  - LoRA: clean ≈ 82.2%, adv ≈ 70.8%  
  - TeCoA: clean ≈ 92.2%, adv ≈ 79.7% (**best trade-off**)

---
Note: Reports and instructions are in **Persian (Farsi)**. An **English version can be provided on request**.
