# PEFT Tutorial: Parameter-Efficient Fine-Tuning with LoRA

This repository provides a hands-on tutorial for fine-tuning transformer models using the Hugging Face PEFT library, focusing on the **LoRA (Low-Rank Adaptation)** method. It demonstrates how to use **parameter-efficient fine-tuning** to adapt a large language model to a text classification task with minimal computational resources.

---

## 🔍 Repository Structure

```
peft-tutorial/
├── index.html               # Static HTML tutorial with explanations and code (for GitHub Pages or offline reading)
├── peft_tutorial.ipynb      # Interactive Jupyter Notebook with all code cells runnable
├── README.md                # Project documentation and structure overview
├── requirements.txt         # Python dependencies (for pip installation)
├── environment.yml          # Conda environment file (recommended setup)
└── results/                 # Output directory for trained models, logs, or evaluations

```

---

## 🚀 Quick Start

### 🧪 Recommended: Create Conda Environment

```bash
conda env create -f environment.yml
conda activate peft-tutorial
```

### 🧩 Alternative: Install via pip

```bash
pip install -r requirements.txt
```

---

## 📘 How to Use

### View the Tutorial

Open `index.html` in your browser for a fully readable version of the tutorial, including math formatting, explanations, and code.

### Run the Code

Open `peft_tutorial.ipynb` using Jupyter Notebook or JupyterLab to run the tutorial interactively.


### Save Outputs

Model checkpoints, logs, and evaluation results will be saved under the `results/` directory after training.

---

## Features Covered

- Introduction to Parameter-Efficient Fine-Tuning (PEFT)
- Overview of LoRA (Low-Rank Adaptation)
- Comparison of encoder-only, decoder-only, and encoder-decoder architectures
- BERT-based text classification using Hugging Face Transformers
- Efficient training using LoRA adapters
- Evaluation using accuracy, precision, recall, and F1-score

---

## Use Cases

This PEFT workflow is suitable for:

- Efficient task-specific adaptation of large pretrained models
- Deploying NLP systems in low-resource or edge-device environments
- Research and teaching related to efficient fine-tuning and transfer learning

---
