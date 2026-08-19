# 📊 Employee Salary & Performance Analysis using Python



A Python-based data analysis project developed to analyze employee salary, experience, department distribution, and performance.



The project demonstrates data inspection, data cleaning, exploratory data analysis (EDA), feature engineering, statistical analysis, data visualization, correlation analysis, and business insight generation using Pandas, NumPy, and Matplotlib.



## 📌 Table of Contents



- [Project Overview](#-project-overview)

- [Objectives](#-objectives)

- [Technologies Used](#-technologies-used)

- [Project Structure](#-project-structure)

- [Dataset Information](#-dataset-information)

- [Data Analysis Process](#-data-analysis-process)

- [Feature Engineering](#-feature-engineering)

- [Statistical Analysis](#-statistical-analysis)

- [Exploratory Data Analysis](#-exploratory-data-analysis)

- [Key Findings](#-key-findings)

- [Business Insights](#-business-insights)

- [Business Recommendations](#-business-recommendations)

- [Project Screenshots](#-project-screenshots)

- [How to Run](#-how-to-run)

- [Python Concepts Demonstrated](#-python-concepts-demonstrated)

- [Future Enhancements](#-future-enhancements)

- [Author](#-author)



---



\# 📖 Project Overview



The Employee Salary \& Performance Analysis project explores a sample employee dataset containing information about employee names, departments, salaries, years of experience, and performance scores.



The project follows a complete exploratory data analysis workflow:



```text

Raw Dataset

&#x20;    ↓

Data Inspection

&#x20;    ↓

Data Cleaning

&#x20;    ↓

Feature Engineering

&#x20;    ↓

Statistical Analysis

&#x20;    ↓

Exploratory Data Analysis

&#x20;    ↓

Data Visualization

&#x20;    ↓

Business Insights



\---



\## 🟦 Objectives



```markdown

\---



\# 🎯 Objectives



The main objectives of this project are:



\- Inspect and understand the employee dataset.

\- Identify the structure and data types of the dataset.

\- Check for missing values and duplicate records.

\- Analyze employee distribution across departments.

\- Calculate salary and performance statistics.

\- Create useful derived features.

\- Analyze salary distribution.

\- Compare departments based on salary and performance.

\- Study the relationship between salary and experience.

\- Identify potential salary outliers using the IQR method.

\- Create visualizations to communicate analytical findings.

\- Generate business insights and recommendations.



\---



\# 🛠 Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Jupyter Notebook



\---



\# 📂 Project Structure



```text

Employee-Salary-Performance-EDA/

│

├── data/

│   ├── employee\_data.csv

│   └── employee\_salary\_performance\_cleaned.csv

│

├── notebook/

│   └── employee\_salary\_performance\_eda.ipynb

│

├── screenshots/

│   ├── 01\_dataset\_overview.png

│   ├── 02\_statistical\_summary.png

│   ├── 03\_employee\_count\_by\_department.png

│   ├── 04\_salary\_distribution.png

│   ├── 05\_average\_salary\_by\_department.png

│   ├── 06\_average\_performance\_by\_department.png

│   ├── 07\_salary\_vs\_experience.png

│   └── 08\_salary\_boxplot.png

│

├── README.md

├── LICENSE

├── requirements.txt

└── .gitignore



\---



\## 🟦 Dataset



```markdown

\---



\# 📊 Dataset Information



The dataset contains information about \*\*8 employees across 4 departments\*\*.



\## Dataset Columns



| Column | Description |

| --- | --- |

| Name | Employee name |

| Department | Employee's department |

| Salary | Employee salary |

| Experience | Years of experience |

| Performance | Employee performance score |



\---



\# 🔍 Data Analysis Process



The project follows several stages of analysis.



\## 1. Data Inspection



The dataset was initially inspected using Pandas functions such as:



\- `head()`

\- `shape`

\- `columns`

\- `dtypes`

\- `info()`

\- `describe()`



These functions were used to understand the structure, size, data types, and statistical characteristics of the dataset.



\## 2. Data Quality Checking



The dataset was checked for:



\- Missing values

\- Duplicate records

\- Unique department values

\- Data types



The analysis found \*\*no missing values and no duplicate rows\*\* in the dataset.



\## 3. Department Analysis



Employee distribution was analyzed using department-level counts.



| Department | Employees |

| --- | ---: |

| IT | 3 |

| HR | 2 |

| Finance | 2 |

| Sales | 1 |

| \*\*Total\*\* | \*\*8\*\* |



\---



\# 🔍 Data Analysis Process



The project follows several stages of analysis.



\## 1. Data Inspection



The dataset was initially inspected using Pandas functions such as:



\- `head()`

\- `shape`

\- `columns`

\- `dtypes`

\- `info()`

\- `describe()`



These functions were used to understand the structure, size, data types, and statistical characteristics of the dataset.



\## 2. Data Quality Checking



The dataset was checked for:



\- Missing values

\- Duplicate records

\- Unique department values

\- Data types



The analysis found \*\*no missing values and no duplicate rows\*\* in the dataset.



\## 3. Department Analysis



Employee distribution was analyzed using department-level counts.



| Department | Employees |

| --- | ---: |

| IT | 3 |

| HR | 2 |

| Finance | 2 |

| Sales | 1 |

| \*\*Total\*\* | \*\*8\*\* |



\---



\# ⚙️ Feature Engineering



Additional categorical features were created from the existing numerical variables.



\## Salary Level



Employees were categorized into salary levels based on salary values.



```text

Salary

&#x20;  ↓

Salary\_Level

&#x20;  ↓

High / Low



\## Performance Level



Employees were categorized according to their performance scores.



```text

Performance

&#x20;     ↓

Performance\_Level

&#x20;     ↓

Excellent / Good / Needs Improvement



These derived features help convert numerical values into meaningful categories for analysis.





\---



\## 🟦 Statistical Analysis



```markdown

\---



\# 📈 Statistical Analysis



The project calculates several descriptive statistics.



\## Salary Statistics



| Metric | Value |

| --- | ---: |

| Average Salary | ₹58,125 |

| Median Salary | ₹57,500 |

| Minimum Salary | ₹45,000 |

| Maximum Salary | ₹72,000 |



\## Experience and Performance



| Metric | Value |

| --- | ---: |

| Average Experience | 4.25 years |

| Average Performance | 85.00 |



\---



\# 📊 Department Analysis



\## Average Salary by Department



| Department | Average Salary |

| --- | ---: |

| IT | ₹69,000 |

| Finance | ₹57,500 |

| Sales | ₹50,000 |

| HR | ₹46,500 |



IT has the highest average salary, while HR has the lowest average salary in this dataset.



\## Average Performance by Department



| Department | Average Performance |

| --- | ---: |

| IT | 91.67 |

| Finance | 86.00 |

| HR | 79.00 |

| Sales | 75.00 |



IT has the highest average performance score, while Sales has the lowest.



\---



\# 🔬 Exploratory Data Analysis



The project uses visualizations to explore important patterns in the dataset.



\## Employee Distribution



A bar chart was created to compare the number of employees across departments.



\## Salary Distribution



A histogram was used to understand how employee salaries are distributed.



\## Average Salary by Department



A bar chart was created to compare average salaries across departments.



\## Average Performance by Department



A bar chart was used to compare department-level performance.



\## Salary vs Experience



A scatter plot was used to investigate the relationship between employee experience and salary.



\## Salary Outlier Analysis



A box plot and the Interquartile Range (IQR) method were used to examine potential salary outliers.



\---



\# 📐 Salary–Experience Correlation



The correlation between salary and experience was calculated using:



```python

df\["Experience"].corr(df\["Salary"])



The resulting correlation is approximately:



0.98



This indicates a very strong positive relationship between experience and salary in this dataset.



Employees with higher experience generally tend to have higher salaries.



However, correlation indicates association and does not necessarily imply causation.





\---



\## 🟦 Markdown Cell 14 — Outlier Analysis



```markdown

\---



\# 📦 Outlier Analysis



The Interquartile Range method was used to identify potential salary outliers.



The calculated values were:



| Measure | Value |

| --- | ---: |

| Q1 | ₹49,500 |

| Q3 | ₹66,250 |

| IQR | ₹16,750 |

| Lower Bound | ₹24,375 |

| Upper Bound | ₹91,375 |



All employee salaries fall within the calculated lower and upper bounds.



Therefore:



> \*\*No potential salary outliers were detected using the IQR method.\*\*



\---



\# 🔍 Key Findings



\### Workforce



The dataset contains \*\*8 employees across 4 departments\*\*.



\### Salary



The average employee salary is \*\*₹58,125\*\*, with salaries ranging from \*\*₹45,000 to ₹72,000\*\*.



\### Highest Average Salary



The \*\*IT department\*\* has the highest average salary at \*\*₹69,000\*\*.



\### Lowest Average Salary



The \*\*HR department\*\* has the lowest average salary at \*\*₹46,500\*\*.



\### Highest Performance



The \*\*IT department\*\* has the highest average performance score at \*\*91.67\*\*.



\### Lowest Performance



The \*\*Sales department\*\* has the lowest average performance score at \*\*75.00\*\*.



\### Largest Department



The \*\*IT department\*\* has the largest number of employees with \*\*3 employees\*\*.



\### Experience



The average employee experience is \*\*4.25 years\*\*.



\### Salary and Experience



Salary and experience have a very strong positive correlation of approximately \*\*0.98\*\* in this dataset.



\---



\# 💡 Business Insights



\## Workforce



IT has the largest workforce with 3 employees, while Sales has only 1 employee. HR and Finance each have 2 employees.



\## Salary



IT has the highest average salary, followed by Finance, Sales, and HR.



The difference in average salary across departments suggests that department-level compensation structures may vary.



\## Performance



IT has the highest average performance score, while Sales has the lowest.



The stronger performance observed in IT may warrant further investigation into factors such as training, workload, experience, or working practices.



\## Salary and Experience



The strong positive correlation between salary and experience suggests that more experienced employees generally receive higher salaries within this dataset.



However, the dataset is small, so this relationship should not automatically be generalized to a larger workforce.



\---



\# 💼 Business Recommendations



\### 1. Performance Improvement



Investigate the practices, training, workload, and other factors that may contribute to the higher performance observed in the IT department.



\### 2. Sales Performance



Review training, workload, incentives, and other factors that may help improve Sales performance.



\### 3. Compensation Analysis



Consider employee experience and performance when evaluating salary and compensation decisions.



\### 4. Workforce Planning



Consider employee distribution, department workload, experience, and performance when planning future hiring.



\### 5. Further Analysis



Analyze additional employee attributes such as job role, tenure, education, and training to better understand differences in salary and performance.



\---



\# 📸 Project Screenshots



\## Dataset Overview



!\[Dataset Overview](screenshots/01\_dataset\_overview.png)



\---



\## Statistical Summary



!\[Statistical Summary](screenshots/02\_statistical\_summary.png)



\---



\## Employee Count by Department



!\[Employee Count by Department](screenshots/03\_employee\_count\_by\_department.png)



\---



\## Salary Distribution



!\[Salary Distribution](screenshots/04\_salary\_distribution.png)



\---



\## Average Salary by Department



!\[Average Salary by Department](screenshots/05\_average\_salary\_by\_department.png)



\---



\## Average Performance by Department



!\[Average Performance by Department](screenshots/06\_average\_performance\_by\_department.png)



\---



\## Salary vs Experience



!\[Salary vs Experience](screenshots/07\_salary\_vs\_experience.png)



\---



\## Salary Distribution and Outliers



!\[Salary Boxplot](screenshots/08\_salary\_boxplot.png)



\---



\# ▶️ How to Run the Project



\## 1. Clone the repository



```bash

git clone https://github.com/MaryShaliniJ/Employee-Salary-Performance-EDA.git



\## 2. Navigate to the project directory



```bash

cd Employee-Salary-Performance-EDA



\## 3. Install the required libraries



```bash

pip install -r requirements.txt



\## 4. Open Jupyter Notebook



```bash

jupyter notebook



\## 5. Open the notebook



Navigate to:



notebook/employee\_salary\_performance\_eda.ipynb



\## 6. Run the notebook



Run the cells sequentially to reproduce the data analysis, visualizations, statistical calculations, and business insights.



\---



\## 🟦 Python Concepts



```markdown

\---



\# 📚 Python Concepts Demonstrated



This project demonstrates:



\- Pandas DataFrames

\- NumPy

\- CSV file handling

\- Dataset inspection

\- Data cleaning

\- Missing-value detection

\- Duplicate detection

\- Filtering

\- Sorting

\- Grouping

\- Aggregation

\- Feature engineering

\- Statistical analysis

\- Correlation analysis

\- IQR-based outlier detection

\- Data visualization

\- Business insight generation



\---



\# 🔮 Future Enhancements



Possible future improvements include:



\- Adding a larger real-world employee dataset.

\- Adding more HR-related variables.

\- Performing employee-level performance analysis.

\- Building an interactive dashboard using Power BI.

\- Creating predictive models for salary or performance.

\- Developing a Streamlit application.

\- Adding more advanced statistical analysis.

\- Automating data refresh and reporting.



\---



\# 👩‍💻 Author



\*\*Mary Shalini J\*\*



M.E. Computer Science and Engineering (Big Data Analytics)

