
# BhashaGuard AI 🛡️

### Explainable Multilingual Misinformation Detection and Evidence-Grounded Response Generation

BhashaGuard AI is a research-oriented NLP and Generative AI project designed to detect and explain potentially misleading information in **Malayalam, English, and Manglish (Malayalam-English code-mixed text)**.

The framework combines multilingual language processing, machine learning, evidence retrieval, and Retrieval-Augmented Generation (RAG) to provide evidence-grounded explanations for online claims.

## 🎯 Objectives

- Identify Malayalam, English, and Manglish text.
- Normalize and process code-mixed language.
- Extract factual claims from user-provided text.
- Classify claims based on available evidence.
- Retrieve relevant information from reliable sources.
- Generate explainable responses with supporting evidence.

## 🏷️ Evidence Classification

BhashaGuard AI aims to classify claims into four categories:

| Label | Meaning |
|---|---|
| Supported | Available evidence supports the claim. |
| Refuted | Available evidence contradicts the claim. |
| Not Enough Evidence | Available evidence is insufficient to verify the claim. |
| Misleading | The claim presents information in a misleading context. |

**Important:** A claim should not be labelled false simply because sufficient evidence has not been found.

## 🧠 Proposed Methodology

1. Language identification
2. Manglish normalization and transliteration
3. Claim extraction
4. Multilingual misinformation classification
5. Evidence retrieval using RAG
6. Explainable, evidence-grounded response generation
7. Interactive application development

## 🛠️ Technologies

- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- XLM-RoBERTa / IndicBERT / MuRIL
- Sentence Transformers
- FAISS or ChromaDB
- SHAP / LIME
- Streamlit

## 📚 Planned Datasets

- DravidianCodeMix – Malayalam-English code-mixed language processing.
- Aksharantar – Indic language transliteration.
- FEVER – Evidence-based claim verification.
- AVeriTeC – Real-world claim verification.
- BhashaGuard-Malayalam – A proposed manually annotated dataset for Malayalam misinformation research.

Dataset licences and usage conditions will be checked before use.

## 🔬 Research Questions

1. Does Manglish normalization improve misinformation detection?
2. How do traditional ML models compare with multilingual transformer models?
3. Does RAG improve the factual reliability of generated explanations?
4. Do evidence-linked explanations improve users' understanding of model predictions?

## 📊 Evaluation

The project will evaluate:

- Classification: Accuracy, Precision, Recall, Macro F1-score.
- Retrieval: Recall@K, MRR and nDCG.
- Generation: Evidence faithfulness and unsupported claim rate.
- Explainability: Interpretability and usefulness of evidence-linked explanations.

## 🚀 Application

The planned application will allow users to submit Malayalam, English, or Manglish text and receive:

- Predicted evidence status
- Relevant supporting information
- Source references
- An understandable explanation

## 📁 Project Structure

```text
BhashaGuard-AI/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── custom/
│
├── notebooks/
│
├── src/
│   ├── preprocessing/
│   ├── models/
│   ├── retrieval/
│   └── evaluation/
│
├── app/
│
├── research/
│   ├── literature_review/
│   └── reports/
│
├── models/
├── requirements.txt
├── README.md
└── .gitignore
```

## 📌 Project Status

<ins>Currently in development.</ins>

The project is being developed in stages, beginning with environment setup, literature review, dataset exploration, and baseline model development.

## 👩‍💻 Research and Development

Developed as an independent research-oriented Data Science project focusing on multilingual NLP, explainable AI, and Generative AI.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

**BhashaGuard AI — Making multilingual information more understandable, explainable, and evidence-aware.**
