# MLOps - Disease Prediction

## 📋 Table of Contents

- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)

## 🛠 Technologies Used

- **Python 3.9+**
- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn
- **Visualization**: matplotlib, seaborn
- **MLOps**: MLflow
- **Data Source**: ucimlrepo
- **Development**: Jupyter Notebook

## 📁 Project Structure

```
mlops-predict-disease-risk/
├── heart_disease_mlops.ipynb    # Main Jupyter notebook with complete pipeline
├── requirements.txt              # Python dependencies
├── best_model.pkl                # Saved best model and scaler
├── mlruns/                       # MLflow experiment tracking data
├── mlops/                        # Virtual environment (if using venv)
│
├── # Generated Visualizations
├── class_balance.png
├── feature_histograms.png
├── feature_boxplots.png
├── correlation_heatmap.png
├── confusion_matrix_logistic_regression.png
├── confusion_matrix_random_forest.png
├── roc_curve_logistic_regression.png
├── roc_curve_random_forest.png
└── model_comparison.png
```

## 🚀 Installation

### Prerequisites

- Python 3.9 or higher
- pip (Python package manager)

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd mlops-predict-disease-risk
```

### Step 2: Create Virtual Environment (Recommended)

```bash

python -m venv mlops

# On macOS/Linux:
source mlops/bin/activate

# On Windows:
mlops\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

## 💻 Usage

### Running the Complete Pipeline

1. **Start Jupyter Notebook**:

```bash
jupyter notebook
```

2. **Open the Notebook**:
   - Navigate to `heart_disease_mlops.ipynb`
   - Run all cells sequentially (Cell → Run All)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

---
