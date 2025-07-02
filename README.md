# Healthcare No-Show Appointment Analysis

This project explores patterns and trends behind missed medical appointments using a real-world dataset. It combines both **Power BI dashboards** and **Python data analysis** to deliver a comprehensive overview of patient behavior.

## 📊 Dashboard (Power BI)

The Power BI report provides interactive visualizations covering:

- **Total Appointments** and **No-Shows**
- **Show Rate by Gender, Age Group, Neighbourhood**
- **SMS Received vs No-Show Rate**
- **Impact of Chronic Conditions (Diabetes, Hypertension)**
- **Average Lead Time before Appointment**
- **Appointment Trends by Day and Age**

> File: [`dashboard/healthcare noshows appointment.pbix`](dashboard/healthcare%20noshows%20appointment.pbix)

![Dashboard Screenshot](screenshots/ssc1.png)

---

## 📈 Exploratory Data Analysis (Python)

Performed in Jupyter Notebook using **Pandas**, **Matplotlib**, and **Seaborn**.

Key steps include:

- Data Cleaning and Preprocessing
- Feature Engineering (Lead Time, Age Bucketing)
- Statistical Analysis of No-Show Patterns
- Correlation between variables like SMS alerts, chronic diseases, and gender

> File: [`analysis/healthcare noshows appointment.ipynb`](analysis/healthcare%20noshows%20appointment.ipynb)

---

## 🧠 Key Insights

- Patients who **didn't receive SMS** are more likely to miss appointments.
- **Younger age groups** tend to have higher no-show rates.
- **Certain neighborhoods** have significantly lower turnout rates.
- Chronic conditions like **diabetes and hypertension** slightly affect show-up behavior.


## ✍️ Author

**Anjali Y** – *MBA Student & Data Analyst Trainee*  
Completed through ThinkMates & Elevate Labs programs.

---

## 📌 Dataset Source

The dataset used for this project is based on real appointment records. (Replace with dataset link if public.)

---

## 📬 Feedback / Contributions

Feel free to fork the repo, open issues, or suggest improvements!



