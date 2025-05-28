# Stack Overflow 2024 – Compensation Deep Dive 💼

This project analyzes developer salaries using the [2024 Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co/2024/). The goal is to explore how factors like country, age, education, and developer role affect yearly compensation.

## 📊 Project Objectives

- Clean and transform salary and demographic data from the survey
- Normalize and log-transform compensation to reduce skew
- Compare salaries across countries, age groups, education levels, and job roles
- Visualize findings using boxplots, bar charts, and heatmaps
- Summarize key insights for developers, hiring managers, and educators

## 🧠 Key Findings

- 🇺🇸 **Top-paying countries**: United States and Canada
- 🧓 **Highest paid age group**: 45–54 years old
- 🎓 **Education premium**: Postgraduate median salary ≈ \$80k
- 👔 **Top roles**: Engineering Managers and Other (specified)


## 🚀 How to Use This Project

### 🔁 1. Clone the Repo
`
git clone https://github.com/<your-username>/so-compensation-deep-dive.git`

`cd so-compensation-deep-dive `

### ⚙️ 2. Create the Conda Environment
`conda env create -f environment.yml`
`conda activate so-compensation`

### 📓 3. Launch the Notebook
`jupyter notebook`

### 🧪 Requirements

Python 3.11+ and the following packages:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- jupyter

All required dependencies are listed in `environment.yml`.

## 📜 License

This project is for educational and portfolio purposes only.  
The dataset is publicly available from Stack Overflow under the terms of their [developer survey license](https://survey.stackoverflow.co/2024/).


