
# Penguin Species Classification Using Machine Learning

This project aims to classify penguin species using the **Palmer Penguins Dataset**. The project follows the **CRISP-DM** methodology to ensure a structured data science workflow.

---

## Project Overview
- **Objective:** Develop a machine learning model to classify penguin species (Adelie, Chinstrap, Gentoo) using biometric features.
- **Dataset:** [Palmer Penguins Dataset](https://allisonhorst.github.io/palmerpenguins/)
- **Methodology:** CRISP-DM
- **Models Used:** Random Forest, Decision Tree, KNN, SVM, and Logistic Regression
- **Final Model:** **Random Forest** (Best accuracy and interpretability)

---

## Features Used
- **Bill Length (mm)**
- **Bill Depth (mm)**
- **Flipper Length (mm)**
- **Body Mass (g)**
- **Island** (Location of observation)
- **Sex** (Male/Female)

---

## Setup Instructions

### Create and Activate a Virtual Environment

Creating a virtual environment ensures isolated dependencies for this project.

**For Ubuntu/Linux:**
```sh
pip install virtualenv
virtualenv .venv
source .venv/bin/activate
```

**For Windows (Command Prompt):**
```sh
pip install virtualenv
virtualenv venv
venv\Scripts\activate.bat
```

**For Windows (PowerShell):**
```sh
pip install virtualenv
virtualenv venv
.\venv\Scripts\Activate
```

---

### Install Dependencies

To install the required dependencies:

```sh
pip install -r requirements.txt
```

---

### Run the Project

1. Open Jupyter Notebook:
```sh
jupyter notebook
```

2. Navigate to the notebook file and run each cell step-by-step.

---

### Verify Installation
To ensure everything is correctly installed:

```sh
python --version
pip freeze
```

---

### Deactivate Virtual Environment
When finished, deactivate the virtual environment:

```sh
deactivate
```

---

## Project Structure

```
📂 Penguin_Classification
├── 📂 data
│   ├── penguins_dataset_w_target.csv
│   ├── processed
│   │   ├── Secondcleaned_dataset.csv
│
├── 📂 notebooks
│   ├── 1_Business_Understanding.ipynb
│   ├── 2_Data_Understanding.ipynb
│   ├── 3_Data_Preparation.ipynb
│   ├── 4_Modeling.ipynb
│   ├── 5_Evaluation.ipynb
│
├── 📂 models
│   ├── best_model_rf.pkl
│
├── 📂 docs
│   ├── index.rst
│   ├── requirements.txt
│
├── .gitignore
├── README.md
```

---

## Key Results
- **Best Model:** **Random Forest** achieved 100% accuracy with clear feature importance insights.
- **Top Features:** Bill Length, Bill Depth, and Flipper Length.
- The model is well-suited for ecological and biological studies.

---

## Research Questions (Answered)
**RQ1:** Can penguin species be accurately classified using the available features?  
**RQ2:** Which features provide the strongest basis for distinguishing between penguin species?  
**RQ3:** Which model achieves the best combination of accuracy and interpretability?  

---

## References
- [Palmer Penguins Dataset](https://allisonhorst.github.io/palmerpenguins/)
- [IBM, "What is Random Forest?" IBM Developer](https://www.ibm.com/think/topics/random-forest)
- CRISP-DM Consortium, *CRISP-DM 1.0: Step-by-Step Data Mining Guide*, 2000. [Online]. Available: [CRISP-DM PDF](https://mineracaodedados.wordpress.com/wp-content/uploads/2012/12/crisp-dm-1-0.pdf)

---

## Contributors
- **Atefeh Karimi**/ Developer
- Special thanks to the data Saxion community and mentors for guidance.