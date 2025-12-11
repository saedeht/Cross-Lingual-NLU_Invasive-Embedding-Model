![GitHub Repo](https://img.shields.io/badge/Research-Paper-blue)
[![DOI](https://img.shields.io/badge/DOI-10.1109%2FACCESS.2025.3574115-blue)](https://dl.acm.org/doi/10.1145/3771926)

# An Invasive Embedding Model in Favor of Low-Resource Languages Understanding

📌 If you use this work, please cite our [paper](https://dl.acm.org/doi/10.1145/3771926) as follows:
```bibtex
@article{tahery2025,
  author    = {Saedeh Tahery and Saeed Farzi},
  title     = {An Invasive Embedding Model in Favor of Low-Resource Languages Understanding},
  journal   = {ACM Transactions on Asian and Low-Resource Language Information Processing},
  year      = {2025},
  url       = {https://dl.acm.org/doi/10.1145/3771926}
}
```
<a href="https://dl.acm.org/doi/10.1145/3771926?cid=99660169355" 
   style="
       display:inline-block;
       padding:10px 16px;
       background:#0059B3;
       color:white;
       text-decoration:none;
       border-radius:6px;
       font-size:15px;
       font-weight:500;
       font-family:sans-serif;
   ">
  ACM Author-Izer Service: Download Paper (PDF)
</a>


## 🗺️ Overview

Cross-lingual natural language understanding (**NLU**) tasks, such as **intent detection (ID) and slot filling (SF)**, suffer from performance degradation due to **language-specific information** embedded in multilingual pre-trained models. This is especially problematic in data-scarce scenarios.  
We propose an **encoder-decoder model with adversarial learning** that eliminates language-specific information while preserving semantic meaning to tackle this issue. Our approach enhances **knowledge transferability** across languages, leading to better zero-shot cross-lingual performance.  

## 🏋️‍♂️ Training and Data Utilization  
The training process consists of a **strategic adversarial learning phase**, where three key components interact dynamically:  
1. **Generator** → Creates language-independent contextual representations.  
2. **Discriminator** → Evaluates representations to detect language identity.  
3. **Decoder** → Reconstructs the original input, ensuring semantic preservation.  

## 📊 Main Results  
Our model demonstrates **strong zero-shot performance** across multiple languages on **Facebook-multilingual (XTOD) and Persian-ATIS** datasets:  

| **Language** | **ID Accuracy** | **SF F1-Score** |  
|-------------|---------------|---------------|  
| **Spanish**  | **94.15**       | **70.44**       |  
| **Thai**     | **82.61**       | **17.60**       |  
| **Persian**  | **86.45**       | **59.60**       |  

