# 📰 Arabic News LLM Fine-Tuning for Content Automation

This project fine-tunes **[Qwen2.5-1.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct)** using **LoRA (Low-Rank Adaptation)** on a dataset of Arabic news articles.  
The goal is to automate **headline extraction, article categorization, and Arabic-to-English translation**, making content management faster and multilingual-ready.

---

## 🚀 Project Overview
- **Model:** Qwen2.5-1.5B-Instruct + LoRA
- **Dataset:** 2,700 Arabic news articles (cleaned & preprocessed)
- **Tasks:**
  - Headline extraction
  - News categorization
  - Arabic-to-English translation
- **Experiment Tracking:** Weights & Biases (W&B)
- **Weak Supervision:** OpenAI GPT for pseudo-labeling

---

## 🛠️ Tech Stack
- Python
- Hugging Face Transformers
- LoRA (via LLaMA Factory)
- OpenAI GPT
- Weights & Biases (W&B) for experiment tracking

---

## 📂 Project Structure
