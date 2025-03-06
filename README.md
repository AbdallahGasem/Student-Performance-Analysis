# Student Performance Insights Challenge

## Overview
This project analyzes a dataset of student performance to uncover insights that can help improve academic outcomes. The analysis includes data cleaning, exploratory data analysis (EDA), and deriving actionable insights to support decision-making for educators and policymakers.

---

## 📊 Dataset
The dataset contains **5,000 records** with the following key attributes:
- **Academic Metrics**: `Attendance (%)`, `Assignments_Avg`, `Quizzes_Avg`, `Midterm_Score`, `Final_Score`, `Total_Score`, `Grade`.
- **Behavioral Metrics**: `Study_Hours_per_Week`, `Stress_Level (1-10)`, `Sleep_Hours_per_Night`.
- **Demographic Metrics**: `Gender`, `Department`, `Parent_Education_Level`, `Family_Income_Level`.
- **Environmental Metrics**: `Extracurricular_Activities`, `Internet_Access_at_Home`.

### Dataset Source
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset).

---

## Project Structure
The project is organized as follows:
```
student-performance-analysis/
├── data/
│   ├── Students_Grading_Dataset.csv          # Raw dataset
│   └── cleaned_students_data.csv             # Cleaned dataset
├── notebooks/
│   └── Student_Performance_Analysis.ipynb    # Jupyter Notebook for EDA
├── reports/
│   └── Student_Performance_Report.pdf        # Final report (if applicable)
├── README.md                                 # Project documentation
```

---

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   cd student-performance-analysis
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Student_Performance_Analysis.ipynb
   ```

---

## 📈 Analysis Workflow
1. **Data Exploration**:
   - Load and explore the dataset.
   - Identify missing values and duplicates.
   - Visualize distributions of key features.

2. **Data Cleaning**:
   - Handle missing values (e.g., imputation, creating "Unknown" categories).
   - Remove irrelevant columns (e.g., `Email`, `First_Name`, `Last_Name`).
   - Handle outliers and inconsistencies.

3. **Feature Engineering**:
   - Encode categorical variables (e.g., `Parent_Education_Level`, `Extracurricular_Activities`).
   - Bin numerical features into categories (e.g., `Stress_Level_Cat`, `Projects_Score_Cat`).

4. **Exploratory Data Analysis (EDA)**:
   - Perform correlation analysis to identify relationships between variables.
   - Visualize trends and patterns using histograms, scatter plots, and heatmaps.

5. **Actionable Insights**:
   - Derive insights to improve academic outcomes.
   - Provide recommendations for educators and policymakers.

---

## 🔍 Key Findings
### Academic Performance
- **Attendance**: Students with higher attendance (81.5% to 85.4%) tend to achieve better grades.
- **Quizzes**: Quizzes have the strongest (though weak) positive correlation with `Total_Score`.
- **Midterm vs. Final Exams**: No significant correlation between midterm and final exam scores.

### Behavioral and Lifestyle Factors
- **Study Hours**: Students with higher grades do not necessarily study more hours.
- **Stress Levels**: Students with medium stress levels perform better than those with high or low stress.
- **Sleep Habits**: Students who sleep an average of 6.4 hours per night tend to perform better.

### Extracurricular and Environmental Factors
- **Extracurricular Activities**: Participation does not harm academic performance.
- **Internet Access**: No significant impact on performance, but it remains a valuable resource.

### Parental and Socioeconomic Factors
- **Parental Education**: Students with more educated parents tend to perform slightly better.
- **Family Income**: Students from low- and medium-income families achieve the highest grades.

---

## Actionable Insights
1. **Improve Attendance**: Track attendance and incentivize good attendance.
2. **Focus on Quizzes**: Provide practice quizzes and study materials.
3. **Promote Effective Study Habits**: Teach time management and active learning techniques.
4. **Manage Stress Levels**: Offer counseling and stress-relief workshops.
5. **Encourage Healthy Sleep**: Educate students on the importance of sleep.
6. **Support Students with Less Educated Parents**: Offer mentorship programs and parent workshops.
7. **Address Income Disparities**: Provide scholarships and subsidized academic resources.

---

## Files
- **`Student_Performance_Analysis.ipynb`**: Jupyter Notebook containing the full analysis.
- **`Students_Grading_Dataset.csv`**: Raw dataset.
- **`cleaned_students_data.csv`**: Cleaned dataset after preprocessing.

---

## Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

## 🙏 Acknowledgments
- Dataset sourced from [Kaggle](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset).
- Special thanks to [DEPI X EYOUTH](https://example.com) for organizing the challenge. 
