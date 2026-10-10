# project-Iris-Flow-IBM
intership project
# Iris Flower Classification using Machine Learning

Author: Saniya Begum Shaikh Lateef

## Project Description
This beginner-friendly machine-learning project classifies Iris flowers into one of three species: setosa, versicolor, or virginica. It uses four flower measurements and a K-Nearest Neighbors (KNN) classifier.

## Dataset
- **Dataset:** Iris dataset (150 records, 4 numeric features, 3 species)
- **Original dataset link:** https://archive.ics.uci.edu/dataset/53/iris
- **How it is loaded:** The notebook uses `sklearn.datasets.load_iris`, so downloading a separate CSV is not required.

## Technologies Used
- Python
- Jupyter Notebook
- pandas
- Matplotlib
- Seaborn
- scikit-learn

## Project Files
- `SaniyaBegumShaikhLateef_IrisFlowerClassification.ipynb` — complete code and analysis
- `requirements.txt` — Python dependencies
- `SaniyaBegumShaikhLateef_ProjectReport.docx` — project documentation
- `README.md` — project overview and run instructions

## Setup Instructions
1. Install Python 3.10 or later.
2. Open a terminal in the project folder.
3. (Optional but recommended) Create and activate a virtual environment:
   - Windows: `python -m venv .venv` then `.venv\\Scripts\\activate`
   - macOS/Linux: `python3 -m venv .venv` then `source .venv/bin/activate`
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Start Jupyter:
   ```bash
   jupyter notebook
   ```
6. Open `SaniyaBegumShaikhLateef_IrisFlowerClassification.ipynb` and choose **Run All**.

## Workflow
1. Load the Iris dataset.
2. Inspect shape, data types, summary statistics, and missing values.
3. Visualize species counts and feature relationships.
4. Split data into training and testing subsets.
5. Scale features and train a KNN classifier.
6. Evaluate performance using accuracy, classification report, and confusion matrix.
7. Predict the species for a sample flower.

## Notes
- The notebook uses a fixed random seed for reproducibility.
- The example prediction is only a demonstration; model output depends on the input measurements.
