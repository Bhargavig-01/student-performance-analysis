
# 🎓 Student Performance Analysis (Excel & Pivot Tables)
> A data analysis project exploring factors influencing student performance using Excel and Pivot Tables.

## 📘 Project Overview

This project analyzes **student performance** data using **Microsoft Excel** and **Pivot Tables** to identify key factors influencing academic outcomes.

The goal is to:

1. Identify the **top 3 factors** positively influencing student performance.
2. Find the **factors negatively affecting** performance (leading to failures).
3. Compare **performance across genders**.

---

## 📊 Dataset Details

**Source:** [Student Classification Dataset](https://www.kaggle.com/datasets/jacksondivakarr/student-classification-dataset)

This dataset includes various demographic, academic, and behavioral details such as:

* **Student_Age, Sex, High_School_Type, Scholarship, Additional_Work, Sports_Activity, Transportation, Weekly_Study_Hours, Attendance, Reading, Notes, Listening_in_Class**, and **Grade**.

Each record represents a unique student and the combination of these attributes provides insights into the factors affecting performance.

---

## 🧭 Objective

1. Identify and analyze the **top 3 factors** positively influencing performance.
2. Highlight the **negative factors** causing failure.
3. Determine **which gender performs better** overall.

---

## ⚙️ Methodology

* Imported dataset into **Excel**.
* Cleaned and structured the data.
* Created a derived column **“Remarks”**:

  * `1` → Pass
  * `0` → Fail
* Used **Pivot Tables**, **Charts**, and **Conditional Formatting** for exploratory analysis.
* Documented insights in a detailed report. 

---

## 📈 Key Findings 
The detailed pivot analysis in [Student_Performance_Analysis](./Student_Performance_Analysis.xlsx) shows that:

### ✅ Top 3 Positive Factors

1. **Attendance**

   * “Always” attendance → 67.59% pass rate
   * Failure rate → only 0.69%

2. **No Extracurricular Involvement**

   * Additional Work (No) → 64.14% pass rate
   * Sports Activity (No) → 57.93% pass rate

3. **Moderate or No Weekly Study Hours**

   * 0 hrs → 61.38% pass rate
   * 2 hrs → 17.93% pass rate

---

### ❌ Negative Factors

| Factor                     | Observation                                   |
| -------------------------- | --------------------------------------------- |
| Not Reading                | 4.14% failure rate                            |
| Bus Transportation         | 4.14% failure (vs. 1.38% for private)         |
| Not Taking Notes           | 3.45% failure                                 |
| Inconsistent Attendance    | 3.45% failure                                 |
| Extracurricular Activities | 3.45% failure (both Additional Work & Sports) |

---

### 👩‍🎓 Gender-wise Performance

| Gender     | Performance Summary                        |
| ---------- | ------------------------------------------ |
| **Male**   | 0% failure rate, slightly fewer top grades |
| **Female** | Higher top grades but includes failures    |

---

## 💡 Insights Summary
All insights were consolidated and visualized in [Student_Performance_Report](./Students_Performance_Report.docx), which highlights:

* **Regular attendance** shows the strongest positive correlation with good performance.
* **Avoiding extracurricular work** improves academic results.
* **Moderate study hours (2–6 hrs)** are more effective than extreme ends.
* **Reading and note-taking** habits significantly improve performance.
* **Male students** performed slightly better overall in this dataset.

---

## 📚 Conclusion

Students who maintain **consistent attendance**, **balance study hours**, and **stay focused without extracurricular distractions** perform significantly better.  
Paying attention in class, reading, and taking notes also play a vital role in improving results.

---

### 🔗 Supporting Files
📄 [View Full Report (Word Document)](./Students_Performance_Report.docx)  
📊 [View Excel Analysis File](./Student_Performance_Analysis.xlsx)


