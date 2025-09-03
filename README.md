# 📊 Student Score Analysis 
📌 Project Overview  
This project analyzes student academic performance across Math, Reading, and Writing subjects. The goal is to explore patterns, relationships, and factors that influence student scores using Python, Pandas, Matplotlib, and Seaborn.

🎯 Objectives :-

To clean and prepare the dataset for analysis.

To understand the distribution of scores across subjects.

To explore correlations between Math, Reading, and Writing scores.

To analyze the impact of parental education, weekly study hours, and transport means on student performance.

To identify key findings and suggest insights for improving academic outcomes.

📂 Dataset

File: student_scores.csv

Key Columns:

MathScore → Student's score in Math

ReadingScore → Student's score in Reading

WritingScore → Student's score in Writing

ParentEduc → Parental education background

WeeklyStudyHours → Hours spent on study per week

TransportMeans → Mode of transport to school

Note: The dataset required minor cleaning (dropping unnecessary Unnamed:0 column).

🛠️ Tools & Libraries

Python 3.x

Pandas – Data cleaning & manipulation

Matplotlib – Data visualization

Seaborn – Advanced plots & statistical visualization

Jupyter Notebook – Interactive analysis

📊 Methodology

Data Cleaning – Removed unnecessary columns, checked missing values, and verified data types.

Exploratory Data Analysis (EDA) –

Distribution of scores in different subjects.

Correlation between Reading, Writing, and Math.

Boxplots to identify outliers.

Factor Analysis –

Effect of parental education on student performance.

Relationship between study hours and scores.

Comparison of transport means with academic performance.

✅ Key Findings / Conclusion

1. Reading & Writing are strongly correlated → Students good in reading usually perform well in writing.

2. Math scores show higher variability → More outliers compared to other subjects.

3. Parental education positively impacts scores → Higher parental education generally leads to better performance.

4. Study hours matter → More weekly study hours improve performance, but the benefit plateaus after a level.

5. Transport time affects performance → Longer commute is linked with slightly lower scores.

📌 How to Run This Project

1. Clone the repository:
   git clone https://github.com/your-username/student-score-analysis.git
   cd student-score-analysis
   
2. Create virtual environment & activate it:
   python3 -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows

3. Install dependencies:
   pip install -r requirements.txt

4. Run Jupyter Notebook:
   jupyter lab

5. Open student_score_analysis.ipynb and run the cells.
