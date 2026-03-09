# Crime Data Analysis in India (2022–2024)

## 1. Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on crime records in India to identify crime patterns, demographic insights, and operational performance indicators.

The goal is to extract actionable insights that can help law enforcement agencies improve resource allocation and public safety strategies.

---

## 2. Business Objective
The main objective of this project is to analyze crime trends and identify:

- Crime distribution patterns
- City-wise crime concentration
- Seasonal and hourly crime trends
- Victim demographic patterns
- Police deployment efficiency
- Case closure performance

---

## 3. Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 4. Dataset Information
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

---

## 5. Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Checked and handled missing values
- Removed duplicate records
- Converted date columns into datetime format
- Created derived features:
  - Year
  - Month
  - Day Name
  - Hour
  - Resolution Days
  - Age Group (Child / Adult / Senior)

These steps improved data quality and enabled time-based and demographic analysis.

---

## 6. Exploratory Data Analysis

The analysis focused on:

- Crime distribution by city
- Crime frequency by hour of the day
- Crime trends by month and year
- Victim demographics
- Police deployment patterns
- Case resolution time

---

## 7. Key Insights

- Overall Case Closure Rate: 49.97% 
- Crime levels remained relatively stable in 2022 and 2023. 
- Higher crime frequency observed from January to July. 
- Theft and assault categories dominate the dataset.
- Major metropolitan cities such as Delhi and Mumbai show the highest crime counts.
- Adults (18–30 years) are the most affected group.
- Female victims represent the highest proportion of reported crimes.
- Police deployment is almost uniform across crime domains (~10 officers on average). 

---

## 8. Recommendations

Based on the analysis:

- Increase Patrol During Peak Crime Hours 
- Improve Case Closure Efficiency 
- Implement targeted crime prevention programs in high-risk cities.
- Implement Women Safety Initiatives 
- Improve investigation processes to reduce case resolution time.
- Use predictive analytics for proactive policing.

---

## 9. Conclusion

This project demonstrates how data analysis can transform raw crime records into actionable insights.

Using Python-based exploratory data analysis, the study identified crime trends, vulnerable demographics, and operational patterns that can support better decision-making for public safety and resource allocation.
