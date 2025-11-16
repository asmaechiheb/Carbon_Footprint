# Carbon_Footprint — Sustainable Language Model Recommendation System

##  Project Overview
Developed a system to reduce the carbon footprint of language model usage by analyzing task complexity and recommending the optimal model in terms of performance, environmental impact, and cost.

This project fine-tunes **DistilBERT**, a transformer-based model, to classify the **complexity level of a task** based on its textual description using **Bloom’s Taxonomy**.  
After predicting the category (e.g., Remember, Understand, Apply, Analyze, Evaluate, Create) and mapping it to a **difficulty level** (Easy, Medium, Hard), the system recommends the most suitable **Large Language Model (LLM)**.  
Simpler tasks are assigned smaller, more energy-efficient models — reducing overall computation and CO₂ emissions.

---

##  Key Features
- Fine-tuning of **DistilBERT** for task complexity classification  
- Mapping Bloom’s Taxonomy categories to practical difficulty levels  
- Intelligent **recommendation of the optimal LLM** for each task  
- Focus on **energy efficiency**, **cost reduction**, and **eco-friendly AI**  
- Extensible architecture for integrating new models and evaluation metrics  

---

##  Project Workflow
1. **Input:** Task description provided by a user or system  
2. **Classification:** DistilBERT predicts the Bloom’s level  
3. **Mapping:** Converts Bloom’s level to difficulty (Easy / Medium / Hard)  
4. **Recommendation:** Suggests the best-suited LLM   
5. **Optimization:** Tracks trade-offs between performance, cost, and carbon footprint  

---

## Repository Structure
Carbon_Footprint/
│
├── Carbon_Footprint_notebook.ipynb # Main Colab notebook with full workflow
├── LLMs_Data_Processing.ipynb # Notebook for LLMs data processing and preparation
├── README.md # Project description and usage guide
└── data/ # Datasets

