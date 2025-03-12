![GitHub Repo](https://img.shields.io/badge/Research-Paper-blue)

# An Invasive Embedding Model in Favor of Low-Resource Languages Understanding

## 📌 Overview
  
Cross-lingual natural language understanding (**NLU**) tasks, such as **intent detection (ID) and slot filling (SF)**, suffer from performance degradation due to **language-specific information** embedded in multilingual pre-trained models. This is especially problematic in data-scarce scenarios.  
We propose an **encoder-decoder model with adversarial learning** that eliminates language-specific information while preserving semantic meaning to tackle this issue. Our approach enhances **knowledge transferability** across languages, leading to better zero-shot cross-lingual performance.  

## 🏋️‍♂️ Training and Data Utilization  
The training process consists of a **strategic adversarial learning phase**, where three key components interact dynamically:  
1. **Generator** → Creates language-independent contextual representations.  
2. **Discriminator** → Evaluates representations to detect language identity.  
3. **Decoder** → Reconstructs the original input, ensuring semantic preservation.  

## 📊 Results  
Our model demonstrates **strong zero-shot performance** across multiple languages on **Facebook-multilingual (XTOD) and Persian-ATIS** datasets:  

| **Language** | **ID Accuracy** | **SF F1-Score** |  
|-------------|---------------|---------------|  
| **Spanish**  | **94.15**       | **70.44**       |  
| **Thai**     | **82.61**       | **17.60**       |  
| **Persian**  | **86.45**       | **59.60**       |  

## 📌 Citation

If you use this work, please cite our [paper]() as follows:
(This will be updated once the paper is accepted.)
```bibtex
@article{tahery2025,
  author    = {Saedeh Tahery and Saeed Farzi},
  title     = {An Invasive Embedding Model in Favor of Low-Resource Languages Understanding},
  journal   = {under-review},
  year      = {2025},
  url       = {will be updated}
}
