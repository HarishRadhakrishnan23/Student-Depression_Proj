# Student Depression Analysis

This project analyzes factors influencing student depression using a machine learning approach. The analysis leverages data preprocessing, exploratory data analysis, and predictive modeling to uncover patterns and build a classifier for detecting depression risks.

## Dataset
The dataset includes features such as:
- **Demographics**: Gender, Age, City
- **Academic and Work Factors**: Academic Pressure, CGPA, Study/Work Hours
- **Lifestyle**: Sleep Duration, Dietary Habits
- **Mental Health Indicators**: Job Satisfaction, Suicidal Thoughts, Family History of Mental Illness

## Project Workflow
1. **Data Preprocessing**:
   - Data cleaning (removal of irrelevant columns like `id`).
   - Handling missing values and outliers.

2. **Exploratory Data Analysis**:
   - Statistical summaries and visualizations to understand key relationships.

3. **Model Training**:
   - Supervised learning models (e.g., Decision Trees, Random Forests, LightGBM).
   - Performance evaluation using metrics like accuracy, recall, and F1-score.

4. **Feature Selection**:
   - Identifying key factors contributing to depression risk.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Scikit-learn, LightGBM, and others.

## Instructions to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/HarishRadhakrishnan23/student-depression-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Student_dep_proj.ipynb
   ```

## Key Findings
- **Correlation Analysis**: Insights into how academic pressure, sleep patterns, and financial stress correlate with depression.
- **Model Performance**: Achieved high accuracy and recall in detecting students at risk of depression.

## Future Scope
- Expanding the dataset to include more diverse demographics.
- Incorporating unsupervised learning for clustering students based on mental health.
- Deploying the model as a web-based diagnostic tool.

## Author
[Harish Radhakrishnan](https://github.com/HarishRadhakrishnan23)
