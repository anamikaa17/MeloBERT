# 🎵 MeloBERT: Emotion Classification from Song Lyrics

MeloBERT is a fine-tuned **BERT-base-uncased** model designed to classify the **emotional valence** (positive / negative mood) of song lyrics.  
Built as part of an experimental research project on **music emotion recognition** using **transformers**.

---

## 🧠 Model Overview
- **Base model:** `bert-base-uncased`
- **Task:** Valence classification (2 classes)
- **Dataset:** Custom dataset `muse_d.csv` (scraped from the Genius API)
- **Architecture:**
  - BERT encoder
  - Custom attention pooling head
  - Dense output layer with softmax
- **Frameworks:** TensorFlow / Hugging Face Transformers
- **Evaluation:** Accuracy ≈ 65%, Macro F1 ≈ 0.63

---

## ⚙️ Training Setup
- Google Colab (GPU runtime)
- Batch size: 16  
- Epochs: 2–3 (≈12 hrs training time)
- Loss: Weighted Cross-Entropy
- Optimizer: AdamW with linear warmup

---

## 📂 Repository Structure
