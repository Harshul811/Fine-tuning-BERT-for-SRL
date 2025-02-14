# Fine-tuning BERT for Semantic Role Labeling (SRL)

This project implements a **PropBank-style Semantic Role Labeling (SRL) system** using **BERT** from the Hugging Face `transformers` library. The model is fine-tuned on the **OntoNotes 5.0** dataset to predict semantic roles in text.

## 📌 Features
- Fine-tunes **BERT** for SRL as a **sequence labeling task** with B-I-O tagging.
- Utilizes **PyTorch** for training and optimization.
- Incorporates **segment embeddings** to encode predicate positions.
- Evaluates model performance using **token-level accuracy and span-based F1 scores**.


