🚢 Titanic Survival Analysis
Data Science Portfolio Project - Exploratory Data Analysis of Titanic passenger survival patterns using Python, Pandas, Matplotlib & Seaborn.

📊 Key Insights
Question	Answer
Who survived more?	👩 Females: 74.2% vs 👨 Males: 18.9%
Class impact?	🛳️ 1st Class: 63.0% > 2nd: 47.3% > 3rd: 24.2%
Age groups?	👶 Kids(0-12): 57.4% > Adults(19-35): 34.4%
🖼️ Visualizations
Survival by Gender	Survival by Class	Age Distribution
![Gender]( ![Class]( ![Age](		
🚀 Features
✅ Data Cleaning: Handle 177 missing Age values (median imputation)

✅ EDA: Answer 3 key survival questions

✅ Visualizations: 3 publication-ready plots

✅ Production Code: No warnings, clean output

✅ Portfolio Ready: Professional analysis

📁 Project Structure
text
Titanic_Analysis/
├── Titanic-Dataset.csv     # Raw dataset (891 passengers)
├── Titanic_Analysis.py     # Main analysis script
├── screenshots/            # Plot screenshots
└── README.md              # This file
🔧 Quick Start
Install dependencies:

bash
pip install pandas matplotlib seaborn
Run analysis:

bash
python Titanic_Analysis.py
Output (3-5 seconds):

text
✅ Data cleaned!
👩 Females survived MORE: 74.2% vs 👨 Males: 18.9%
🛳️ YES! Class1: 63.0% > Class2: 47.3% > Class3: 24.2%
👶 Kids(0-12): 57.4% | Adults(19-35): 34.4%
[3 PLOTS]
💻 Code Highlights
python
# Clean missing Age values
df['Age'] = df['Age'].fillna(df['Age'].median())

# Professional visualizations  
sns.countplot(data=df, x='Sex', hue='Survived')
sns.countplot(data=df, x='Pclass', hue='Survived')
plt.hist(df['Age'], bins=30, edgecolor='black')
📈 Skills Demonstrated
Data Cleaning: Missing value imputation

EDA: Groupby analysis, survival rates

Visualization: Seaborn + Matplotlib

Python: Pandas data manipulation

Best Practices: Clean, warning-free code

📊 Dataset
Titanic Dataset - 891 passengers:

Survival (0/1), Pclass, Age, Sex, Fare

177 missing Age values (handled)

🎯 Business Takeaways
Women & Children First - 74% female vs 19% male survival

Class Privilege - 1st class 3x more likely to survive

Children Priority - Kids(0-12) 57% survival rate

👨‍💻 Author
Data Science Student
Early-career Data Scientist | Python | ML | Visualization
