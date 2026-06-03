# 🏋️ Gym Members Exercise Tracking Analysis

A data science project that analyzes gym members’ workout habits and fitness performance using Python. The project explores how factors such as workout type, session duration, gender, age, water intake, workout frequency, and experience level affect calories burned.

---

## 📌 Project Overview

The goal of this project is to identify the most effective workout strategies for achieving fitness goals based on gym members’ exercise tracking data.

The analysis uses exploratory data analysis, visualizations, correlation analysis, and hypothesis testing to understand workout patterns and extract meaningful insights.

---

## 🎯 Objectives

This project aims to answer the following questions:

- Which workout type burns the most calories on average?
- How does session duration affect calories burned?
- Is water intake related to calories burned?
- Does age affect calories burned?
- Do males and females burn calories differently?
- How does workout frequency differ by gender and workout type?
- Does Cardio burn more calories than HIIT?

---

## 📊 Dataset

The dataset used in this project is:

`gym_members_exercise_tracking.csv`

It contains information about gym members, including their personal details, workout habits, and fitness performance.

### Main Features

| Column | Description |
|---|---|
| `Age` | Age of the gym member |
| `Gender` | Gender of the gym member |
| `Weight (kg)` | Weight in kilograms |
| `Height (m)` | Height in meters |
| `Max_BPM` | Maximum heart rate during workout |
| `Avg_BPM` | Average heart rate during workout |
| `Resting_BPM` | Resting heart rate |
| `Session_Duration (hours)` | Workout session duration |
| `Calories_Burned` | Calories burned during the workout |
| `Workout_Type` | Type of workout performed |
| `Fat_Percentage` | Body fat percentage |
| `Water_Intake (liters)` | Water intake during workout |
| `Workout_Frequency (days/week)` | Number of workout days per week |
| `Experience_Level` | Gym experience level |
| `BMI` | Body Mass Index |

---

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook / Google Colab

---

## 🔄 Project Workflow

The project follows these main steps:

1. Importing the required libraries
2. Loading the dataset
3. Exploring the dataset structure
4. Checking for missing values
5. Performing univariate analysis
6. Performing bivariate and multivariate analysis
7. Creating data visualizations
8. Calculating correlations
9. Performing hypothesis testing
10. Summarizing the main findings

---

## 📈 Key Insights

### 1. Session Duration and Calories Burned

There is a strong positive relationship between workout session duration and calories burned.

**Correlation = 0.908**

This means that longer workout sessions are strongly associated with burning more calories.

---

### 2. Average Calories Burned by Workout Type

| Workout Type | Average Calories Burned |
|---|---:|
| HIIT | 925.81 |
| Strength | 910.70 |
| Yoga | 903.19 |
| Cardio | 884.51 |

HIIT had the highest average calories burned, followed by Strength training, Yoga, and Cardio.

---

### 3. Water Intake and Calories Burned

Water intake had a weak positive relationship with calories burned.

**Correlation = 0.357**

This suggests that members who drank more water tended to burn slightly more calories, but water intake alone is not a strong predictor of calories burned.

---

### 4. Age and Calories Burned

Age had a weak negative relationship with calories burned.

**Correlation = -0.155**

This means older members tended to burn slightly fewer calories on average, but the relationship was weak.

---

### 5. Workout Frequency by Gender and Workout Type

| Workout Type | Gender | Average Workout Frequency |
|---|---|---:|
| Cardio | Female | 3.24 days/week |
| Cardio | Male | 3.23 days/week |
| HIIT | Female | 3.32 days/week |
| HIIT | Male | 3.38 days/week |
| Strength | Female | 3.33 days/week |
| Strength | Male | 3.39 days/week |
| Yoga | Female | 3.50 days/week |
| Yoga | Male | 3.23 days/week |

Female members practicing Yoga had the highest workout frequency, while male members practicing Strength and HIIT also showed high workout frequency.

---

## 🧪 Hypothesis Testing

A hypothesis test was performed to check whether Cardio burns more calories than HIIT.

### Hypotheses

**Null Hypothesis:**  
The mean calories burned during Cardio sessions is less than or equal to the mean calories burned during HIIT sessions.

**Alternative Hypothesis:**  
The mean calories burned during Cardio sessions is greater than the mean calories burned during HIIT sessions.

### Results

| Metric | Value |
|---|---:|
| Z-Score | -1.6487 |
| P-Value | 0.9504 |

### Conclusion

Since the p-value is very high, we fail to reject the null hypothesis.

There is not enough statistical evidence to prove that Cardio burns more calories than HIIT. Based on the dataset, HIIT actually had a higher average calorie burn than Cardio.

---

## ✅ Final Conclusion

The analysis shows that session duration is the strongest factor related to calories burned. Members who worked out for longer periods generally burned more calories.

HIIT had the highest average calorie burn among the workout types, followed by Strength training. The results also showed that Cardio did not burn more calories than HIIT in this dataset.

Other factors such as water intake, age, gender, experience level, and workout frequency provide useful context, but they were not as strongly related to calories burned as session duration.

Overall, this project demonstrates how data science can be used to analyze fitness behavior and support better workout decisions.

---

## 📂 Project Structure

```text
.
├── Copy_of_Data_Science_2_Project.ipynb
├── gym_members_exercise_tracking.csv
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### 2. Navigate to the Project Folder

```bash
cd your-repository-name
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy
```

### 4. Open the Notebook

```bash
jupyter notebook
```

Then open:

```text
Copy_of_Data_Science_2_Project.ipynb
```

You can also run the notebook using Google Colab.

---

## 🧠 Skills Demonstrated

- Python programming
- Data exploration
- Exploratory Data Analysis
- Data visualization
- Correlation analysis
- Hypothesis testing
- Statistical interpretation
- Fitness data analysis
- Communicating insights clearly

---

## 🔮 Future Improvements

Possible future improvements include:

- Building a machine learning model to predict calories burned
- Creating an interactive dashboard using Power BI, Tableau, or Streamlit
- Adding more advanced statistical testing
- Including more features such as diet, sleep, and workout intensity
- Creating personalized workout recommendations

---

## 👥 Authors

- Beshoy M. Botros
- Ahmed M. Monir
