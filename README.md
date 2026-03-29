## 📊 Notebooks & Workflow

### Notebook 1: Data Collection
- Downloads peptide sequences
- Predicts MHC Class I binding (IEDB)
- Predicts T-cell epitope potential
- **Output:** `epitope_prediction_combined.csv`

### Notebook 2: Exploratory Data Analysis (EDA)
- Statistical analysis of predictions
- Identifies strong binders
- Creates visualizations
- **Output:** `strong_binders_for_molecular_docking.csv`

### Notebook 3: Molecular Docking Analysis
- Downloads HLA-A*02:01 protein structure
- Performs binding energy predictions
- Compares IEDB vs docking results
- **Output:** Docking results & visualizations

### Notebook 4: ML Model for Epitope Prediction (Coming Soon)
- Trains machine learning model
- Uses docking data for validation
- Predicts new epitopes

## 🚀 Quick Start

1. **Open in Google Colab:** Click the Colab badge on each notebook
2. **Run in order:** Notebook 1 → 2 → 3 → 4
3. **Download results:** All CSV and PNG files are saved automatically

## 📥 Data Flow
