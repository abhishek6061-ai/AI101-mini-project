# Project title: Predicting Personal Loan Approval Using Logistic Regression
- Our model uses a customer's details (income, age, credit card spending, mortgage amount) to predict whether their personal loan will be approved or not.

- AI101 Mini-Project, IIT Ropar | Team 51

## Team,Github ID,Role and Entry No.

| Name | GitHub | Role | Entry No. |
|---|---|---|---|
| Abhishek Yadav | abhishek6061-ai | Documentation lead | 2026AIB1003 |
| Rajveer Dabi | rajveer-mcb | Execution lead | 2026MCB1558 |
| Shobhan | shobhan-vn | PPT lead | 2026EEB1423 |
| Shivansh | shivansh-009 | Video lead | 2026EEB1411 |

**All members contributed code to the project.**

## Problem and Dataset
- **Problem:** Banks need to decide which customers are likely to be approved for a personal loan. We predict whether a customer's loan is approved (1) or not (0) from details such as income, age, credit card spending and mortgage amount. This can make lending decisions faster and more consistent.
- **Dataset:** Bank Loan Approval dataset (Kaggle): https://www.kaggle.com/datasets/vikramamin/bank-loan-approval-lr-dt-rf-and-auc
- **Size:** 5000 rows x 14 columns
- **Target variable:** Personal Loan (Binary: 1 for approved/accepted, 0 for rejected/not accepted)
- **Task:** Logistic regression

## Project Structure

```
AI101-mini-project/
├── README.md                 
├── requirements.txt          
├── data/
│   └── bankloan.csv
├── notebook/
    ├── your_notebook.ipynb
    └── output/
        ├── Feature Correlation with Personal Loan.png
        ├── Feature Correlation Heatmap.png
        ├── ROC Curve.png
        ├── Validation Loss Curve.png
        └── Learning Curve.png         
├── results/                  
└── slides/
    └── [filename].pdf        
```

## Setup

- Python version: 3.14.6
- **Install libraries:**

```bash
pip install -r requirements.txt
```

## How to Run the Notebook

### Prerequisites
- [Git](https://git-scm.com/downloads)
- [Python 3.14+](https://www.python.org/downloads/)

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/abhishek6061-ai/AI101-mini-project.git
cd AI101-mini-project
```

**2. Create a virtual environment**
Windows (Git Bash):
```bash
python -m venv venv
source venv/Scripts/activate
```

Windows (Command Prompt / PowerShell):
```bash
python -m venv venv
venv\Scripts\activate
```

macOS / Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```
**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Go into the notebook folder**
```bash
cd notebooks
```

**5. Launch Jupyter Notebook**
```bash
jupyter notebook
```
Your browser will open automatically. If it doesn't, copy the `http://localhost:8888/...` link from the terminal.

**6. Open and run the notebook**
- Click `main.ipynb`
- Run all cells: **Kernel → Restart & Run All**
  (or press `Shift + Enter` to run cell by cell)

## Expected Output

[Add a screenshot from results/ showing what a correct run looks like.]

## Results
- Accuracy = [0.xx]
- Precision = [0.xx], Recall = [0.xx], F1 = [0.xx]
- [One-line interpretation for the problem statement]

## Slides and Video

- Slides (PDF, 5 slides): [link to slides/filename.pdf]
- Video (3 to 5 minutes, all members speak): [unlisted or public YouTube link]

## AI Tool Disclosure

| Tool | Used for | How we verified it |
|---|---|---|
| Claude | Debugging | Run the code and checked results ourselves |
