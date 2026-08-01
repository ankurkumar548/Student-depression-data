# Student Depression Analysis Using Tableau

## Project Overview

This project analyzes factors associated with depression among students using Tableau. It explores how academic pressure, study satisfaction, sleep duration, dietary habits, financial stress, study hours, family history of mental illness, and suicidal thoughts may relate to student depression.

The project includes an interactive Tableau dashboard that helps users explore patterns and relationships within a dataset containing **502 student records**.

## Dashboard Preview

![Student Depression Analysis Dashboard](images/student-count-dashboard.png)

## Project Files

- **Tableau Workbook:** `First Project.twbx`
- **Original Data Source:** `Depression_students1.csv`
- **Dataset Size:** 502 records
- **Workbook Type:** Tableau Packaged Workbook
- **Data Storage:** Embedded Tableau Hyper Extract

The dataset is embedded inside the `.twbx` file, so the workbook can be opened without separately downloading the CSV file.

## Dataset Features

| Column | Description |
|---|---|
| `Gender` | Gender of the student |
| `Age` | Age of the student |
| `Age_Group` | Age-group category |
| `Academic_Pressure` | Level of academic pressure |
| `Study_Satisfaction` | Satisfaction level with studies |
| `Study_Hours` | Number of hours spent studying |
| `Sleep_Duration` | Average sleep-duration category |
| `Dietary_Habits` | Quality of dietary habits |
| `Financial_Stress` | Level of financial stress |
| `Family_History_of_Mental_Illness` | Family history of mental illness |
| `Have_you_ever_had_suicidal_thoughts` | Reported history of suicidal thoughts |
| `Depression` | Depression status of the student |
| `index_column` | Unique record index |

## Project Objectives

- Analyze depression patterns among students.
- Examine academic pressure across the student population.
- Understand the distribution of financial stress.
- Compare depression across different genders and age groups.
- Analyze students based on sleep duration and dietary habits.
- Study the relationship between study satisfaction and student count.
- Explore the distribution of students according to study hours.
- Identify factors that may be associated with a higher risk of depression.

## Dashboard Visualizations

### 1. Academic Pressure Analysis

This visualization shows the distribution of students across five academic-pressure levels. Academic-pressure level 3 contains the highest number of students, with **125 records**.

![Academic Pressure Analysis](images/academic-pressure-analysis.png)

### 2. Financial Stress Analysis

This visualization presents the number of students at each financial-stress level. Financial-stress level 1 contains the highest number of students, with **110 records**.

![Financial Stress Analysis](images/financial-stress-analysis.png)

### 3. Study Satisfaction Analysis

This chart compares student counts across five study-satisfaction levels. Study-satisfaction level 4 has the highest student count, with **116 records**.

![Study Satisfaction Analysis](images/study-satisfaction-analysis.png)

### 4. Sleep Duration Analysis

This visualization groups students according to their reported sleep duration. The categories **7–8 hours** and **more than 8 hours** contain the highest counts, with **128 students each**.

![Sleep Duration Analysis](images/sleep-duration-analysis.png)

### 5. Study Hours Analysis

This area chart displays the distribution of students according to their daily study hours. The highest observed category contains **53 students**.

![Study Hours Analysis](images/study-hours-analysis.png)

### 6. Combined Student Count Dashboard

The final Tableau dashboard combines financial stress, study hours, study satisfaction, sleep duration, and academic pressure into a single analytical view.

![Combined Student Count Dashboard](images/student-count-dashboard.png)

## Key Findings

- Academic-pressure level 3 has the highest count with **125 students**.
- Financial-stress level 1 has the highest count with **110 students**.
- Study-satisfaction level 4 has the highest count with **116 students**.
- Both the **7–8 hours** and **more than 8 hours** sleep categories contain **128 students**.
- Student distribution varies across study-hour categories, with the highest category containing **53 students**.
- The dashboard provides a consolidated view of the academic and lifestyle characteristics represented in the dataset.

> These observations describe the distribution of records in the dataset. They do not prove that any factor causes depression.

## Key Analysis Areas

- Depression distribution by gender
- Depression distribution by age group
- Academic pressure and student count
- Financial stress and student count
- Sleep duration and mental health
- Dietary habits and depression
- Study satisfaction and study hours
- Family history of mental illness
- History of suicidal thoughts

## Tools and Technologies

- Tableau
- Tableau Hyper Extract
- CSV
- Data Visualization
- Exploratory Data Analysis
- Dashboard Design

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/Student-Depression-Analysis.git
```

2. Open the cloned repository:

```bash
cd Student-Depression-Analysis
```

3. Install [Tableau Public](https://public.tableau.com/) or Tableau Desktop.

4. Open the packaged workbook:

```text
First Project.twbx
```

5. Open the dashboard and interact with the available worksheets and visualizations.

## Repository Structure

```text
Student-Depression-Analysis/
├── First Project.twbx
├── Depression_students1.csv
├── README.md
└── images/
    ├── academic-pressure-analysis.png
    ├── financial-stress-analysis.png
    ├── study-satisfaction-analysis.png
    ├── sleep-duration-analysis.png
    ├── study-hours-analysis.png
    └── student-count-dashboard.png
```

## Future Improvements

- Add interactive filters for gender, age group, and depression status.
- Add KPI cards for total students, depressed students, and depression rate.
- Analyze depression status directly across each contributing factor.
- Improve chart labels and standardize the dashboard colour palette.
- Replace abbreviated labels such as `SC`, `AP`, and `FS` with descriptive names.
- Add calculated fields for percentage-based comparisons.
- Publish the completed dashboard on Tableau Public.
- Add a direct Tableau Public dashboard link to the repository.

## Disclaimer

This project was created for educational and exploratory purposes only. Its findings should not be used for medical diagnosis or treatment. Relationships observed in the dataset do not necessarily indicate causation.

## Author

**Ankur Kumar**

B.Tech in Electrical Engineering  
National Institute of Technology Agartala
