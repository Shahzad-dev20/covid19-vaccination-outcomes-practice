# 💉 COVID-19 Vaccination Outcomes Practice

End-to-end pandas data cleaning on real COVID-19 
vaccination outcomes data.

## 📥 Dataset
| | Link |
|--|------|
| 📂 Raw Data | [Download](https://drive.google.com/file/d/1fJ-j52Nd8Ehmq8eCkhEEhw320Aq4ZcZ1/view?usp=drive_link) |
| 📂 Cleaned Data | [Download](https://drive.google.com/file/d/1goaF8EMGjI9Yf7csdvLM-QxZ9UFWp3WA/view?usp=drive_link) |

## 📊 Dataset Info
- Source: CDC COVID-19 Vaccination Outcomes
- Raw: 3,753 rows | 21 columns
- Cleaned: 3,336 rows | 18 columns

## 🔧 What I Did
- Dropped Age-Adjusted columns (80%+ missing)
- Checked skewness before filling missing values
- Filled with median (skewed columns)
- Dropped 'All' age group rows
- Encoded Outcome and Age Group with natural order
- Extracted Year, Month, Week from date column
- Capped outliers using IQR clip method

## 🧠 Key Findings
- Unvaccinated rate significantly higher than vaccinated
- Boosted population had lowest outcome rates
- Elderly age groups showed highest outcome numbers

## 🚀 Next Steps
- Train regression/classification model using sklearn
- Compare outcomes across vaccination status
- Visualize trends with Matplotlib

## 🛠️ Tools Used
- Python 3 | Pandas | NumPy | Jupyter Notebook

## 👤 Author
**Shahzad**
Practicing data science for job/internship applications.
```

