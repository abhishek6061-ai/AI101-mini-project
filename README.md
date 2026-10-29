# [Project title,Predicting Home Loan Approval from Applicant Income, Credit card average score,mortgage Amount and  Using Logistic Regression]

[One line: what the project predicts, from which dataset, using which model.]

AI101 Mini-Project, IIT Ropar | Team [51]

## Team and Roles

| Name | GitHub | Role | Entry No. |
|---|---|---|
| [Abhishek Yadav] | abhishek6061-ai | Documentation lead | 2026AIB1003 |
| [Rajveer Dabi] | [rajveer-mcb] | Execution lead | 2026MCB1558 |
| [Shobhan] | [shobhan-vn] | PPT lead | 2026EEB1423 |
| [Shivansh] | [shivansh-009] | Video lead | 2026EEB1411 |

All members contributed code to the project.

## Problem and Dataset

- **Problem:** [Loan Approval ]
- **Dataset:** [Predicting Home Loan Approval from Applicant Income, Credit card average score,mortgage Amount]; file: https://www.kaggle.com/datasets/vikramamin/bank-loan-approval-lr-dt-rf-and-auc
- **Size:** [5000 rows x 14 columns]
- **Target variable:** [Personal Loan (Binary: 1 for approved/accepted, 0 for rejected/not accepted)]
- **Task:** [Logistic regression]

## Project Structure

```
AI101-mini-project/
├── README.md                 # this file
├── requirements.txt          # Python libraries
├── data/
│   └── [banlloan].csv        # dataset used
├── notebooks/
│   └── [main].ipynb          # full code: preprocessing, training, evaluation
├── results/                  # plots and output screenshots
└── slides/
    └── [filename].pdf        # 5-slide presentation
```

## Setup

- Python version: [3.14.6]
- **Install libraries:**
  ```bash
  pip install -r requirements.txt

## How to Run the Notebook

### Prerequisites
- [Git](https://git-scm.com/downloads)
- [Python 3.9+](https://www.python.org/downloads/)

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/abhishek6061-ai/AI101-mini-project.git
cd AI101-mini-project
```

**2. Create a virtual environment**

Windows:
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


**4. Launch Jupyter Notebook**
```bash
jupyter notebook
```
Your browser will open automatically. If it doesn't, copy the `http://localhost:8888/...` link from the terminal.

**5. Open and run the notebook**
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
| [e.g. Claude] | [e.g. README structure, debugging] | [e.g. ran the code and checked results ourselves] |
