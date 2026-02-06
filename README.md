# 🚦 Traffic Accident Severity Analysis

## 📌 Project Overview
This project analyzes traffic accident data to understand the key factors influencing accident severity. Using exploratory data analysis (EDA), the study examines how driver characteristics, driving experience, weather, lighting, and road conditions contribute to the severity of road accidents.

The goal is to transform raw accident records into actionable safety insights that can support better road safety policies and awareness.

---

## 📊 Dataset Description
The dataset consists of categorical driver, vehicle, and environmental attributes along with a numerical accident severity label.

**Key Columns:**
- Age_band_of_driver
- Sex_of_driver
- Educational_level
- Vehicle_driver_relation
- Driving_experience
- Lanes_or_Medians
- Types_of_Junction
- Road_surface_type
- Light_conditions
- Weather_conditions
- Type_of_collision
- Vehicle_movement
- Pedestrian_movement
- Cause_of_accident
- Accident_severity (Target Variable)

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Accident Severity Distribution
- Most accidents fall under the **highest severity category**, indicating a strong class imbalance.
- Minor severity cases are comparatively rare.

### 2. Severity by Driver Age Group
- Drivers aged **18–30 and 31–50** are involved in the highest number of severe accidents.
- Underage drivers show fewer accidents overall, but severity is still present.

### 3. Severity by Driving Experience
- Drivers with **5–10 years of experience** account for a large portion of severe accidents.
- Very low experience (below 1 year) also shows notable severity risk.
- Unlicensed drivers, although fewer, are involved in serious accidents.

### 4. Severity by Weather Conditions
- Most accidents occur during **normal weather**, highlighting that accidents are not limited to extreme conditions.
- Rainy and windy conditions still show a noticeable rise in severity.

### 5. Severity by Light Conditions
- **Daylight** has the highest number of accidents due to higher traffic volume.
- **Darkness with limited or no lighting** shows relatively higher severity risk per accident.

### 6. Severity by Road Surface Type
- **Asphalt roads** account for the majority of accidents.
- Gravel and damaged asphalt roads, while fewer, contribute to severe outcomes.

---

## 🧠 Key Insights
- Accident severity is influenced more by **human and infrastructural factors** than extreme weather alone.
- Moderate driving experience does not necessarily reduce risk.
- Poor lighting and suboptimal road conditions increase accident severity.
- Road safety interventions should focus on driver behavior, lighting infrastructure, and road maintenance.

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 📌 Conclusion
This analysis highlights that improving road safety requires more than addressing weather-related risks. Driver awareness, experience management, proper lighting, and road surface quality play a critical role in reducing accident severity.

Future extensions may include predictive modeling to classify accident severity using machine learning.
