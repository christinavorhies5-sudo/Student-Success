# Student-Success
An end-to-end data analysis project identifying key predictors of student success and dropout risk using a dataset of 4,424 students. Features interactive visualizations and SQL-based insights built with Python, DuckDB, and Plotly

# Student Success & Dropout Risk Analysis

This project explores a dataset of 4,424 students to identify key predictors of academic success and dropout risk. Using Python, SQL (DuckDB), and interactive visualizations (Plotly), I analyzed how demographics, socio-economic status, and academic performance influence student outcomes.

## 🔍 Key Insights
* **Financial Impact:** Students with overdue tuition fees have a **86.5% dropout rate**, making it the strongest predictor of risk.
* **Gender Gap:** Male students showed a significantly higher dropout rate (**45.0%**) compared to female students (**25.1%**).
* **Age Factor:** "Mature" students (31+) face higher challenges, with a dropout rate of **53.6%**.
* **Scholarship Success:** Scholarship holders have a very high retention rate, with only a **12.2%** dropout rate.

## 🛠️ Tools & Technologies
* **Data Processing:** Pandas, NumPy
* **Database/SQL:** DuckDB, SQLAlchemy
* **Visualization:** Plotly (Interactive), Seaborn, Matplotlib
* **Environment:** Google Colab

## 📊 Analysis Highlights
The project includes several interactive visualizations, including:
1.  **Demographic Heatmaps:** Gender vs. Marital Status risk.
2.  **Socio-Economic Bar Charts:** Impact of debt and scholarships.
3.  **Academic Efficiency:** Comparison of enrolled vs. approved units per semester.
4.  **Course Performance:** Scatter plot mapping average grades against dropout rates per major.

## 📂 Project Structure
* `student_success_project.ipynb`: The full analysis and visualization code.
* `Cleaned_Data.xlsx`: The dataset used for the study.
* `README.md`: Project overview and summary of findings.

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed: `pip install pandas plotly duckdb`.
3. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
