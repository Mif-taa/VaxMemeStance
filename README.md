## 📄 CUET_SYNTHETICA@EEUCA 2026
### Gated Cross-Modal Attention with Domain-Adapted Text Encoding for Vaccine-Critical Meme Detection

**Authors:**
- Sumaiya Zaman
- Miftahul Jannat Rishta
- Shiti Chowdhury

**Venue:** Proceedings of the 9th Workshop on Event Extraction and Understanding: Challenges and Applications (EEUCA 2026)
**DOI:** [10.18653/v1/2026.eeuca-1.14](https://doi.org/10.18653/v1/2026.eeuca-1.14)

#### 🧩 Overview
This work addresses the EEUCA 2026 Shared Task on Multimodal Vaccine-Critical Meme Detection, classifying memes from the **VaxMeme dataset** into three categories: **Vaccine-Critical**, **Neutral**, and **Pro-Vaccine**. Vaccine-critical memes combine images and text to spread misinformation in ways that are difficult to detect automatically, making this a genuinely multimodal problem.

#### 🏗️ Architecture
- **Text encoder:** Twitter-RoBERTa (domain-adapted for social media text)
- **Visual encoder:** CLIP ViT-L/14
- **Fusion:** Gated cross-modal attention combining text and image representations
- Multiple text encoders and visual backbones were experimented with; the domain-specific Twitter-RoBERTa + CLIP combination outperformed larger general-purpose models — showing domain adaptation matters more than raw model scale.

🏆 **Result:** Test Macro F1 = **0.8357**, securing **3rd place** on the shared task leaderboard.

#### 📚 Citation
```bibtex
@inproceedings{zaman-etal-2026-cuet-synthetica,
    title = "{CUET}{\_}{SYNTHETICA}@{EEUCA} 2026: Gated Cross-Modal Attention with Domain-Adapted Text Encoding for Vaccine-Critical Meme Detection",
    author = "Zaman, Sumaiya  and
      Rishta, Miftahul Jannat  and
      Chowdhury, Shiti",
    editor = {H{\"u}rriyeto{\u{g}}lu, Ali  and
      Thapa, Surendrabikram  and
      Tanev, Hristo},
    booktitle = "Proceedings of the 9th Workshop on Event Extraction and Understanding: Challenges and Applications ({EEUCA} 2026)",
    month = jul,
    year = "2026",
    address = "San Diego, California, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.eeuca-1.14/",
    doi = "10.18653/v1/2026.eeuca-1.14",
    pages = "133--140",
    ISBN = "979-8-89176-402-6"
}
```
