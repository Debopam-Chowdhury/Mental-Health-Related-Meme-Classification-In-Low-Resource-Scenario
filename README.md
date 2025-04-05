# 🌐 Hinglish Meme Dataset for Mental Health Classification

> 🧠 *A curated collection of over 7,000 Hinglish memes to explore mental health discourse in South Asian digital spaces.*

---

## 📚 Table of Contents
- [✨ Overview](#-overview)
- [🗂️ Dataset Description](#-dataset-description)
- [🧪 Methodology](#-methodology)
- [📝 Annotation Guidelines](#-annotation-guidelines)
- [📊 Dataset Statistics](#-dataset-statistics)
- [🚀 Usage](#-usage)
- [👨‍💻 Contributors](#-contributors)
- [📖 Citation](#-citation)
- [🙏 Acknowledgements](#-acknowledgements)

---

## ✨ Overview

This dataset bridges a critical gap in culturally and linguistically relevant mental health research within the South Asian context. It contains **7,000+ memes** in **Hinglish** (Hindi-English hybrid language), classified as either **mental health** or **non-mental health** content.

Mental health-related memes are further divided into six disorders to allow granular analysis and training of AI models in a multimodal setting.

---

## 🗂️ Dataset Description

Each entry in the dataset includes:

- 🖼️ **Meme Image**
- 🔤 **Extracted Text** (via OCR)
- 🧠 **Image Context** (via vision-language model)
- 🏷️ **Label** (mental health / non-mental health)

### 🧩 Mental Health Subcategories

1. **Narcissistic Personality Disorder**
2. **Intermittent Explosive Disorder**
3. **Delusional Disorder**
4. **Suicidal Ideation**
5. **Anxiety Disorder**
6. **Depressive Disorder**

---

## 🧪 Methodology

This dataset is built using a **multimodal AI pipeline** combining three powerful models:

| Stage | Model | Description |
|-------|-------|-------------|
| 🔍 **Text Extraction** | **Gemini OCR** | Extracts text embedded in meme images |
| 🖼️ **Image Context** | **LLaVA (Large Language and Vision Assistant)** | Interprets the visual tone, expression, and scene |
| 🧠 **Classification** | **Self-Conversational GPT-4 AI** | Determines final category and subcategory |

---

## 📝 Annotation Guidelines

### ✅ Mental Health Memes
- Highlight **internal struggles** or **emotional distress**
- Use **humor as a coping mechanism**
- Include signs of **exhaustion**, **confusion**, or **mental strain**
- Refer to **psychological symptoms or conditions**

### ❌ Non-Mental Health Memes
- Focus on **external events** and **social interactions**
- Use **situational or pop culture humor**
- Avoid depicting personal mental health challenges

> Detailed annotation instructions for each subcategory are provided in the dataset documentation.

---

## 📊 Dataset Statistics

| Metric | Value |
|--------|-------|
| 🧮 **Total Memes** | 7,000+ |
| 🗃️ **Format** | CSV / JSON |
| 🌐 **Language** | Hinglish (Hindi-English hybrid) |
| 🌍 **Sources** | Google Images, Instagram, Pinterest, Telegram |

---

## 🚀 Usage

This dataset is useful for:

- 🧠 Training mental health **classification models**
- 🌍 Studying **cultural representations** of mental health online
- 🛡️ Building **content moderation** systems for South Asian platforms
- 🔁 Researching **code-switching** in emotional communication

---

## 👨‍💻 Contributors

Developed by:

- **Aarush Sen** (2206312)  
- **Anikesh Datta** (2206322)  
- **Ayush Gupta** (2206255)  
- **Ayush Ojha** (2206254)  
- **Debopam Chowdhury** (2206257)  
- **Divyendra Singh** (2206259)  

> Under the guidance of **Dr. Tanik Saikh**  
> *School of Computer Engineering, KIIT Deemed to be University*

---

## 📖 Citation

If you use this dataset in your research, please cite:

```bibtex
@dataset{hinglish-meme-mental-health,
  title = {Hinglish Meme Dataset for Mental Health Classification},
  author = {Sen, Aarush and Datta, Anikesh and Gupta, Ayush and Ojha, Ayush and Chowdhury, Debopam and Singh, Divyendra},
  year = {2025},
  note = {KIIT University},
  url = {https://github.com/<your-repo-link>}
}
