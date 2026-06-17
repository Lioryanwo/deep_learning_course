<div align="center">

# 🧠 Deep Learning Course — Assignments & Projects (B.Sc.)

<p>
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-Deep_Learning-EE4C2C?logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-From_Scratch-013243?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib%20%2F%20Seaborn-Visualization-11557C" />
  <img src="https://img.shields.io/badge/Level-B.Sc.-success" />
</p>

<i>From manual gradient derivations to modern architectures — a structured journey through deep learning.</i>

</div>

---

## 📖 Overview

This repository collects the assignments and projects completed during my **B.Sc. Deep Learning** course. The coursework deliberately follows a progression: it starts from **theoretical foundations and by‑hand derivations**, moves through **building neural network components from scratch in NumPy**, and ends with **state‑of‑the‑art architectures implemented in PyTorch** across vision, time‑series, and audio domains.

Each module is self‑contained, with a runnable notebook and a high‑fidelity PDF export for easy reading.

---

## 🗺️ Learning Progression

| # | Module | Topic | Key Skills |
|:---:|---|---|---|
| 1 | `Prov-The-Gradients` | Backpropagation & gradient math | Manual derivations, chain rule, gradient checking |
| 2 | `NN_Implementation` | Neural network from scratch | Layers, activations, loss functions in NumPy |
| 4 | `CNN_Fashion_MNIST` | Convolutional networks | CNN design, hyperparameter tuning, image classification |
| 5 | `Transfer_Learning` | Transfer learning | Fine‑tuning ResNet18, feature extraction vs. full training |
| 6 | `GRU_Stock_Prices` | Recurrent networks | Time‑series forecasting with GRUs |
| 7 | `Audio_Dataset` | Audio modeling | Audio data processing & classification |

---

## 🛠️ Technologies & Tools

- **Core frameworks:** PyTorch, NumPy
- **Data processing:** Pandas
- **Visualization:** Matplotlib, Seaborn
- **Architectures:** Feed‑Forward Networks (from scratch), CNNs, RNNs (GRU), Transfer Learning (ResNet18), audio models

---

## 📂 Repository Structure

The repository is organized by assignment module, reflecting the progression above.

```text
.
├── data/                              # Shared dataset storage
│
├── Homework_1_Prov-The-Gradients/
│   ├── Code.ipynb                     # Mathematical proofs of gradients & initial experiments
│   └── PDF_Format.pdf                 # High-fidelity export of the notebook
│
├── Homework_2_NN_Implementation/
│   ├── Code.ipynb                     # Building NN components (layers, loss) from scratch
│   └── PDF_Format.pdf                 # High-fidelity export
│
├── Homework_04_CNN_Fashion_MNIST/
│   ├── Code.ipynb                     # End-to-end CNN architecture & hyperparameter tuning
│   ├── practice CNN.ipynb             # Supplementary sandbox for testing CNN concepts
│   └── PDF_Format.pdf                 # High-fidelity export
│
├── Homework_5_Transfer_Lerning/
│   ├── Code.ipynb                     # Transfer learning using ResNet18
│   ├── Report_Document.ipynb          # Analysis: fine-tuning vs. training from scratch
│   ├── ResNet18_FashionMNIST.pth      # Pre-trained model weights
│   └── PDF_Format.pdf                 # High-fidelity export
│
├── Homework_6_GRU_Stock_Prices/
│   └── Code.ipynb                     # Time-series forecasting using Gated Recurrent Units (GRU)
│
├── Homework_7_Audio_Dataset/
│   └── Code.ipynb                     # Audio dataset processing & classification
│
└── README.md
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone <your-repo-url>
cd Deep_Learning_Course_git

# (Recommended) create a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# Install the core dependencies
pip install torch numpy pandas matplotlib seaborn jupyter
```

Open any module's notebook to run it:

```bash
jupyter notebook Homework_04_CNN_Fashion_MNIST/Code.ipynb
```

> Prefer just reading? Each module ships a `PDF_Format.pdf` export of the notebook.

---

## 📌 Module Highlights

- **Homework 1 — Prove the Gradients:** derive backpropagation by hand and validate it numerically, building intuition for how gradients flow through a network.
- **Homework 2 — NN Implementation:** implement the building blocks (linear layers, activations, loss) in pure NumPy, with no autograd to lean on.
- **Homework 4 — CNN on Fashion‑MNIST:** design and tune a convolutional classifier end to end, with a separate sandbox notebook for experimentation.
- **Homework 5 — Transfer Learning:** adapt a pretrained ResNet18 to Fashion‑MNIST and compare fine‑tuning against training from scratch; trained weights are included.
- **Homework 6 — GRU Stock Prices:** forecast time‑series data with Gated Recurrent Units.
- **Homework 7 — Audio Dataset:** process and model audio data for classification.

---

## 🧹 Suggested Cleanups (optional)

A few folder names contain small typos worth fixing for a polished repo. If you rename the folders, update the tree above so links stay valid:

- `Homework_1_Prov-The-Gradients` → `Homework_1_Prove-The-Gradients`
- `Homework_5_Transfer_Lerning` → `Homework_5_Transfer_Learning`
- Consider consistent numbering (`Homework_04_...` vs `Homework_4_...`) across all modules.

---

<div align="center">
  <i>A structured walk through deep learning — one derivation, one architecture, one dataset at a time.</i>
</div>
