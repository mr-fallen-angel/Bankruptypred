# Taiwanese Bankruptcy Prediction

This model analyzes financial ratios of Taiwanese companies to predict bankruptcy, using machine learning models and a modular Python pipeline.

---

## Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/572/taiwanese+bankruptcy+prediction)
- **Size:** 6,819 company instances (1999–2009)
- **Features:** 95 financial ratios
- **Target Variable:** `Bankrupt?` (1 = Bankrupt, 0 = Not Bankrupt)

---

## Project Structure

```
.
├── bankrupt_final_clean.ipynb       # Original Jupyter notebook
├── main_modular_script.py           # Modular notebook-style script
├── utils.py                         # General-purpose helper functions
├── my_bankruptcy_project.py         # Domain-specific logic (e.g., plotting)
├── bankruptcy_model.py              # Model definition and training logic
├── requirements.txt                 # Project dependencies
```

---

## Getting Started

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run the Project
- Open the notebook or run `main_modular_script.py`
- Ensure the dataset is downloaded and accessible
- 
---

## Acknowledgments

- Dataset: [UCI ML Repo – Taiwanese Bankruptcy Prediction](https://archive.ics.uci.edu/dataset/572/taiwanese+bankruptcy+prediction)
