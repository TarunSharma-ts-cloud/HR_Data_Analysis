# HR Data Analysis with Python 📊

A data analysis project exploring a Human Resources dataset using Python. The notebook answers 15 real-world HR business questions through data wrangling, aggregation, and visualization.

---

## 📁 Dataset

The analysis uses `HR_Data.csv`, which contains employee-level records with the following key fields:

| Column | Description |
|---|---|
| `Employee_ID` | Unique employee identifier |
| `Department` | Department the employee belongs to |
| `Job_Title` | Employee's job role |
| `Status` | Employment status (Active, Resigned, Retired, Terminated) |
| `Work_Mode` | Work arrangement (On-site / Remote) |
| `Salary_INR` | Salary in Indian Rupees |
| `Performance_Rating` | Numerical performance score |
| `Experience_Years` | Years of experience |
| `Hire_Date` | Date of joining |
| `Location` | Employee location (City, Country) |

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** — data loading, cleaning, and aggregation
- **Matplotlib** — bar charts, pie charts, and line plots
- **Seaborn** — count plots and correlation heatmaps

---

## ❓ Business Questions Answered

1. What is the distribution of Employee Status (Active, Resigned, Retired, Terminated)?
2. What is the distribution of work modes (On-site vs. Remote)?
3. How many employees are there in each department?
4. What is the average salary by department?
5. Which job title has the highest average salary?
6. What is the average salary in different departments based on job title?
7. How many employees Resigned & Terminated in each department?
8. How does salary vary with years of experience?
9. What is the average performance rating by department?
10. Which country has the highest concentration of employees?
11. Is there a correlation between performance rating and salary?
12. How has the number of hires changed over time (per year)?
13. Do Remote and On-site employees earn significantly different salaries?
14. Who are the top 10 highest-paid employees in each department?
15. Which departments have the highest attrition rate (Resigned %)?

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas matplotlib seaborn
```

### Run the Notebook

1. Clone this repository:
```bash
   git clone https://github.com/your-username/hr-data-analysis-with-python.git
   cd hr-data-analysis-with-python
```

2. Place the `HR_Data.csv` file in the same directory as the notebook.

3. Launch Jupyter Notebook:
```bash
   jupyter notebook hr-data-analysis-with-python.ipynb
```

---

## 📌 Key Insights

- **Employee status** breakdown is visualized using a pie chart with percentage labels.
- **Attrition analysis** identifies which departments suffer the most from resignations.
- **Salary trends** are explored across departments, job titles, experience levels, and work modes.
- **Correlation heatmap** reveals relationships between numeric variables like salary, experience, and performance rating.
- **Hiring trends** are tracked year-over-year using hire date extraction.

---

## 📂 Project Structure
