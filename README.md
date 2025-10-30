# README

## Project: Offline Reinforcement Learning for Credit Approval

### 1. Setup Instructions

1. **Clone or download** the project folder.
2. Ensure you have **Python 3.10+** installed.
3. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the main notebook file (e.g., `offline_rl_credit.ipynb`).

### 2. Running the Project

Follow these steps inside the notebook:

1. **Step 1 – Data Preparation:** Load and preprocess the Lending Club dataset.
2. **Step 2 – Train Supervised Model:** Run the cell titled *Supervised PyTorch MLP*. This trains the default probability predictor and outputs AUC/F1.
3. **Step 3 – Run Reward-Greedy Policy:** Execute the next section to compute the Expected Policy Value (EPV) and compare supervised vs RL policies.
4. **Step 4 – Analyze Results:** Visualizations and comparison summaries will appear automatically.

### 3. Outputs
- Model metrics (AUC, F1)
- Expected Policy Value (EPV)
- Reward comparison tables and policy difference examples
- Plots for ROC, Precision-Recall, and Policy Performance

### 4. Notes
- Ensure the dataset file (e.g., `accepted_2007_to_2018.csv`) is placed inside a `/data` directory.
- If you encounter missing directory errors, create an `artifacts/` folder for result storage.

---

# requirements.txt
```
numpy==1.26.4
pandas==2.2.2
matplotlib==3.9.0
scikit-learn==1.5.0
torch==2.3.0
d3rlpy==2.8.1
jupyterlab==4.2.0
```

