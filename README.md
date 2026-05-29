# 🩺 AI-Based Clinical Deterioration Prediction System

This project presents a multi-generation deep learning framework for predicting clinical deterioration and sepsis using physiological data, sequential patient monitoring, and transformer-based clinical note analysis.

---

# 📁 Project Structure

The project is divided into **3 notebooks**, where each notebook represents a different AI approach.

## Generation 1 — DNN Baseline

Focuses on:

* Deep Neural Network (DNN)
* Feature engineering
* Optimizer comparison (SGD vs Adam)
* SMOTE for class balancing
* Clinical risk prediction using structured vitals

### Features

* Shock Index
* Pulse Pressure
* Low Oxygen Flag

### Outputs

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Loss/Accuracy Curves

---

## Generation 2 — Sequential Modeling

Focuses on temporal patient monitoring using:

* LSTM
* GRU
* Bidirectional LSTM (BiLSTM)

### Includes

* Sequential window generation
* Transfer learning with pretrained recurrent weights
* Training time comparison
* Real-time vs retrospective analysis

---

## Generation 3 — ClinicalBERT

Focuses on transformer-based clinical NLP using:

* Bio_ClinicalBERT

### Includes

* Clinical note tokenization
* Frozen vs full fine-tuning
* Attention visualization
* Important clinical term extraction
* Per-class deterioration analysis

### Example Important Terms

* respiratory
* oxygen
* temperature
* heart rate
* blood pressure
---

# How to Run

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

Run notebooks:

* `Generation1_DNN.ipynb`
* `Generation2_SequentialModels.ipynb`
* `Generation3_ClinicalBERT.ipynb`

Department of Artificial Intelligence
Faculty of Information & Computing Sciences
