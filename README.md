# AI Assistant Usage Among College Students

## Overview
I analyzed survey-style data about AI assistant usage in student life. The notebook explores how students use AI tools and what patterns appear in the dataset.

## Motivation
I connect this project to my interest in human-AI interaction and responsible AI use. I used it to practice exploratory analysis on a current social and technical question.

## Dataset
- **File:** `data/ai_assistant_usage_student_life.csv`
- **Target variable:** I did not define a supervised target for this version.
- **Known limitations:** Survey data may reflect sampling bias, self-reporting bias, and limited generalizability.

## Methods
- I loaded the student AI-assistant usage dataset.
- I performed exploratory data analysis in a Jupyter Notebook.
- I examined usage patterns and feature distributions.
- I generated visual summaries for interpretation.

## Results
I treat this as an exploratory project, so I do not report a single model metric. The value is in the analysis of student AI-use patterns and the questions it raises for future human-AI research.

## Key Insights
- AI assistant usage can be studied as both a technical and behavioral question.
- Survey framing matters because self-reported usage can be biased.
- This project is a useful starting point for more rigorous human-AI interaction work.

## Limitations
- I do not make causal claims about AI assistant use.
- The dataset source and sampling process need clearer documentation.
- Survey responses may not represent all college students.

## How to Run
```bash
git clone https://github.com/BobbY-24/Artificial-Intelligence-Market-Among-College-Student-.git
cd Artificial-Intelligence-Market-Among-College-Student-
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/ai_assistant_usage_student_life.ipynb
```
