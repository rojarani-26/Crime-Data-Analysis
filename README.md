# 🚔 Crime Data Analysis in India (2022–2024)


## 📌 Project Overview
This project performs an **end-to-end Exploratory Data Analysis (EDA)** on crime records in India to identify crime patterns, demographic insights, and operational performance indicators.

The goal is to extract **actionable insights** that can help law enforcement agencies improve **resource allocation and public safety strategies**.


## 🎯 Business Objective
The main objective of this project is to analyze crime trends and identify:

🔹 Crime distribution patterns  
🔹 City-wise crime concentration  
🔹 Seasonal and hourly crime trends  
🔹 Victim demographic patterns  
🔹 Police deployment efficiency  
🔹 Case closure performance  


## 🛠 Tools & Technologies
This project was completed using the following tools:

🐍 **Python**  
📊 **Pandas**  
🔢 **NumPy**  
📈 **Matplotlib**  
💻 **Google Colab / Jupyter Notebook**


## 📂 Dataset Information
The dataset contains **22,616 crime records** with the following attributes:

| Column | Description |
|------|-------------|
| Report Number | Unique crime report ID |
| Date Reported | Date when crime was officially reported |
| Date of Occurrence | Actual date when crime occurred |
| Time of Occurrence | Time when crime occurred |
| Location | Crime location |
| Crime Code | Unique code for crime type |
| Crime Description | Description of crime |
| Victim Age | Age of victim |
| Victim Gender | Gender of victim |
| Weapon Used | Weapon involved in crime |
| Crime Domain | Category of crime |
| Police Deployed | Number of officers assigned |
| Case Closed | Case resolution status |
| Date Case Closed | Date when case was closed |


## 🧹 Data Cleaning & Preprocessing
The following preprocessing steps were performed to improve data quality:

✔ Checked and handled missing values  
✔ Removed duplicate records  
✔ Converted date columns into **datetime format**

### ➕ Feature Engineering
Additional features were created to support analysis:

📅 **Year**  
📅 **Month**  
📅 **Day Name**  
⏰ **Hour**  
📊 **Resolution Days**  
👥 **Age Group (Child / Adult / Senior)**

These steps enabled **time-based and demographic analysis**.


## 📊 Exploratory Data Analysis
The analysis focused on the following areas:

📍 Crime distribution by city  
⏰ Crime frequency by hour of the day  
📆 Crime trends by month and year  
👥 Victim demographics  
👮 Police deployment patterns  
📑 Case resolution time  


## 🔍 Key Insights

📊 **Overall Case Closure Rate:** 49.97%  

📈 Crime levels remained relatively **stable in 2022 and 2023**.

📅 Higher crime frequency observed **between January and July**.

🚨 **Theft and assault** are the most common crime categories.

🏙 Major metropolitan cities such as **Delhi and Mumbai show the highest crime counts**.

👥 **Adults (18–30 years)** are the most affected victim group.

👩 **Female victims represent the highest proportion** of reported crimes.

👮 Police deployment is relatively **uniform across crime domains (~10 officers on average)**.


## 💡 Recommendations

🚔 **Increase patrols during peak crime hours** to improve prevention.

⚡ **Improve case closure efficiency** through faster investigation processes.

🏙 Implement **targeted crime prevention programs in high-risk cities**.

👩 Enhance **women safety initiatives and protection programs**.

📊 Use **predictive analytics for proactive policing strategies**.


## 🏁 Conclusion

This project demonstrates how **data analysis can transform raw crime records into actionable insights**.

Using **Python-based exploratory data analysis**, the study identified crime trends, vulnerable demographics, and operational patterns that can support **better decision-making for public safety and resource allocation**.
