# Project title: Predicting Home Loan Approval from Applicant Income, Credit card average score,mortgage Amount and  Using Logistic Regression

- Our model uses a customer's details (income, age, credit card spending) to predict whether their personal loan will be approved or not

- AI101 Mini-Project, IIT Ropar | Team [51]

## Team,Github ID,Role and Entry No.

| Name | GitHub | Role | Entry No. |
|---|---|---|---|
| Abhishek Yadav | abhishek6061-ai | Documentation lead | 2026AIB1003 |
| Rajveer Dabi | rajveer-mcb | Execution lead | 2026MCB1558 |
| Shobhan | shobhan-vn | PPT lead | 2026EEB1423 |
| Shivansh | shivansh-009 | Video lead | 2026EEB1411 |

**All members contributed code to the project.**

## Problem and Dataset

- **Problem:** Loan Approval 
- **Dataset:** Predicting Home Loan Approval from Applicant Income, Credit card average score,mortgage Amount;
- file: https://www.kaggle.com/datasets/vikramamin/bank-loan-approval-lr-dt-rf-and-auc
- **Size:** 5000 rows x 14 columns
- **Target variable:** Personal Loan (Binary: 1 for approved/accepted, 0 for rejected/not accepted)
- **Task:** Logistic regression

## Project Structure

```
AI101-mini-project/
├── README.md                 
├── requirements.txt          
├── data/
│   └── [banlloan].csv        
├── notebooks/
│   └── [main].ipynb          
├── results/                  
└── slides/
    └── [filename].pdf        
```

## Setup

- Python version: [3.14.6]
- **Install libraries:**
  ```bash
  pip install -r requirements.txt

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
cd notebook
```

**5. Launch Jupyter Notebook**
```bash
jupyter notebooks
```
Your browser will open automatically. If it doesn't, copy the `http://localhost:8888/...` link from the terminal.

**6. Open and run the notebook**
- Click `main.ipynb`
- Run all cells: **Kernel → Restart & Run All**
  (or press `Shift + Enter` to run cell by cell)

## Expected Output

[Add a screenshot from results/ showing what a correct run looks like.]

## Results

- [Key metric 1, e.g. Test R2 = 0.xx]
- [Key metric 2]
- [One-line interpretation for the problem statement]

## Slides and Video

- Slides (PDF, 5 slides): [link to slides/filename.pdf]
- Video (3 to 5 minutes, all members speak): [unlisted or public YouTube link]

## AI Tool Disclosure

| Tool | Used for | How we verified it |
|---|---|---|
| Claude | Debugging | Run the code and checked results ourselves |
