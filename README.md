# 📊 HR Analytics — Employee Turnover Analysis

A data analysis project that explores the key factors driving employee attrition using Exploratory Data Analysis (EDA) and data visualization techniques.

---

## 📁 Project Structure

```
HR_ANALYTICS_PROJECT/
│
├── HR_ANALYTICS.ipynb       # Main Jupyter Notebook
├── README.md                # Project documentation
└── data/                    # Dataset folder
```

---

## 🎯 Objective

To analyze HR data and identify the key drivers of employee turnover — helping organizations make data-driven decisions to improve employee retention.

---

## 📌 Dataset Overview

| Feature | Description |
|---|---|
| `left` | Target variable — 1 if employee left, 0 if stayed |
| `satisfactoryLevel` | Employee satisfaction score (0 to 1) |
| `numberOfProjects` | Number of projects assigned |
| `avgMonthlyHours` | Average monthly working hours |
| `timeSpent.company` | Number of years spent in the company |
| `promotionInLast5years` | Whether promoted in the last 5 years (0/1) |
| `salary` | Salary level — low / medium / high |

---

## 📊 Visualizations & Key Findings

### 1. Employee Turnover Distribution
- ~76% of employees **stayed**, ~24% **left**
- Dataset has a **class imbalance** — important for ML modeling

### 2. Number of Projects vs Attrition
- Employees with **2 projects** (underutilized) and **6–7 projects** (overworked) are most likely to leave
- **3–5 projects** is the sweet spot for retention

### 3. Promotion vs Turnover
- **1,983 employees left without a single promotion** in 5 years
- Lack of career growth is a **major attrition driver**

### 4. Tenure vs Turnover
- The **3–4 year mark** is the most critical attrition window
- Employees who cross 5+ years tend to stay long-term

### 5. Satisfaction vs Projects vs Monthly Hours
- Low satisfaction clusters around fewer projects and irregular hours
- Clear divide between satisfied and dissatisfied employee groups

### 6. Satisfaction Level Distribution
- Bimodal distribution — two distinct employee groups
- Large group with **very low satisfaction (~0.1)**

### 7. Projects vs Average Monthly Hours
- Strong **positive correlation** — more projects = more hours
- Overloaded employees burn out and eventually leave

### 8. Salary Distribution
- **47.9% low salary | 43.9% medium | 8.3% high**
- Low compensation combined with no promotions = highest attrition risk

---

## 🔑 Overall Conclusions

1. **Low salary + no promotion = highest attrition risk**
2. **3–4 year employees** need the most retention focus
3. **Overworked employees (6–7 projects)** burn out and leave
4. **Underutilized employees (2 projects)** disengage and leave
5. A significant portion of employees have **very low satisfaction**, strongly predicting turnover

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation & analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive development environment |

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/hr-analytics.git
cd hr-analytics
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook HR_ANALYTICS.ipynb
```

---

## 👤 Author

**HARSH KAUSHIK**
- LinkedIn: [www.linkedin.com/in/harshkaushik315]


- GitHub: [https://github.com/harshkaushik315]

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
