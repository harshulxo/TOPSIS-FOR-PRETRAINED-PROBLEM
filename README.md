# Conversational AI Model Evaluation using TOPSIS

## 📌 Overview
This project evaluates **lightweight conversational AI models** using **response similarity, inference speed, and model size**. It ranks models using the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method to determine the best model for chatbot applications.

## 🎯 Objectives
- Compare **pre-trained causal language models**.
- Measure **response similarity** (cosine similarity).
- Evaluate **inference speed** (execution time).
- Simulate **model size** (storage requirement).
- Rank models using **TOPSIS** for **multi-criteria decision-making**.
- Visualize results in a **table and bar chart**.

---

## 🏗️ How It Works
1. **Load and Test Models** → Models are evaluated using sample **conversation prompts**.
2. **Extract Response Embeddings** → Compute cosine similarity between model outputs.
3. **Measure Performance Metrics**:
   - **Response Similarity** → How well the model maintains context.
   - **Inference Speed** → How fast the model generates responses.
   - **Model Size** → Approximate storage space used.
4. **Apply TOPSIS Ranking** → Ranks models by comparing best & worst cases.
5. **Visualize and Save Results** → Displays a **ranked table and bar chart**.

---

## ⚙️ Models Used
| Model | Description |
|--------|------------|
| **EleutherAI/gpt-neo-125M** | Small GPT model (good for text generation) |
| **facebook/opt-125m** | Smallest OPT model from Facebook |
| **bigcode/santacoder** | Causal model trained for code/text generation |

✅ **All models are freely available** and require **no authentication**.

---

## 🛠️ Installation & Dependencies
Ensure you have **Python 3.8+** installed.

### 📦 **Step 1: Install Required Packages**
Run the following command:
```bash
pip install torch transformers pandas numpy matplotlib scikit-learn

