# AxisInsurance-Analysis
This project uses statistical analysis and hypothesis testing to explore a health insurance dataset. We analyze how factors like smoking, gender, and number of children influence medical charges, using Python libraries like pandas, seaborn, and SciPy to uncover actionable insights.

# 📊 Hypothesis Testing in Health Insurance Data

📝 Overview

This project applies hypothesis testing techniques to explore insights from customer data of a health insurance company. The primary focus is on analyzing whether specific customer attributes—like smoking habits, BMI, and number of children—affect medical insurance charges. The goal is to derive statistically supported business insights.

# 🎯 Objectives
	•	Perform Exploratory Data Analysis (EDA) on the insurance dataset.
	•	Use hypothesis testing to answer business-critical questions.
	•	Interpret and visualize statistical results to support decision-making.

 # 📂 Project Structure
 ├── Applied_Statistic_Project.ipynb   # Main Jupyter notebook
├── data/                             # (If applicable) Dataset used
├── README.md                         # Project documentation
└── requirements.txt                  # Python dependencies

# 📚 Dataset Description

The dataset Axisinsurance.csv includes the following features:
	•	Age: Age of the customer
	•	Sex: Gender (Male/Female)
	•	BMI: Body Mass Index
	•	Children: Number of dependents
	•	Smoker: Smoking status (Yes/No)
	•	Region: U.S. region of residence
	•	Charges: Medical insurance costs billed

 # 🔍 Questions Answered with Hypothesis Testing
	1.	📈 Do smokers claim significantly higher medical charges than non-smokers?
	2.	🧍 Is the BMI of females significantly different from that of males?
	3.	🗺️ Does smoking habit depend on the region?
	4.	👶 Is the mean BMI of women with 0, 1, or 2 children the same?

	All hypothesis tests are conducted at a significance level of 0.05.

 # 🧪 Techniques Used
	•	Two-sample T-tests
	•	Chi-square test for independence
	•	One-way ANOVA
	•	Visualization: Boxplots, Countplots, Histograms

 # 💻 Technologies
	•	Python 3.x
	•	pandas, NumPy
	•	Matplotlib, Seaborn
	•	SciPy

 # 🚀 How to Run
	1.	Clone the repository:
                           git clone https://github.com/your-username/hypothesis-testing-insurance.git
                            cd hypothesis-testing-insurance
 	2.	Install dependencies:
                            pip install -r requirements.txt

  3.	Run the notebook:
                         jupyter notebook Applied_Statistic_Project.ipynb

# 📄 License

This project is licensed under the MIT License.
                        
