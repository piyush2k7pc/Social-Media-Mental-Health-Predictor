# Social-Media-Mental-Health-Predictor
Advanced Python mini-project: cleaning and analysing social media &amp; mental health data, exploring correlations between screen time, stress, anxiety, and sleep.
# Social Media vs Mental Health – Data-Driven Analysis using Python

This project analyzes how **social media usage patterns** (screen time, platform usage, etc.) affect **mental health indicators** such as stress, anxiety, mood, and sleep.  
Using Python, we clean a real-world style dataset, perform exploratory data analysis (EDA), compute correlations, and visualize patterns to understand the relationship between social media and mental well-being. 

---

## 🎯 Project Objectives

- Analyze the **impact of social media usage** on mental health.
- Identify **key negative factors** such as high screen time and low sleep.
- Explore both **positive and negative effects** of social media.
- Use **Python data analysis tools** to clean, transform, and visualize the dataset.
- Present insights clearly for **academic / presentation** purposes.

---

## 📊 Dataset Overview

We primarily work with a CSV dataset containing self-reported metrics on social media usage and health.

Typical columns include: 

- `user_id` – Unique participant ID  
- `age` – Age of the participant  
- `gender` – Gender category  
- `daily_screen_time` – Total hours on social media per day  
- `screen_time_before_sleep` – Phone usage (hours) before sleep  
- `platform_used_most` – Most used app (Instagram, WhatsApp, etc.)  
- `stress_level` (1–10)  
- `anxiety_level` (1–10)  
- `sleep_hours_avg` – Average sleep per day (hours)  
- `mood_level` (1–10)  
- `physical_activity` – Daily exercise (minutes)  
- `academic_performance` – Percentage score  
- `social_interaction_real_life` – Frequency of offline interaction  
- `device_addiction_score`  
- `comments_or_posts_per_day`  
- `mental_health_status` – Overall label (Good / Moderate / Poor)

### Files used

- `social_media_health_extended_big.csv` – Raw / extended dataset  
- `social_media_health_clean.csv` – Cleaned dataset ready for analysis  

---

## 🧠 Problem Statement

With the rapid rise of social media usage, especially among students and young adults, there is growing concern about its impact on mental health.  
This project uses **structured data + Python** to study how different levels of social media usage relate to:

- Stress
- Anxiety
- Mood
- Sleep quality
- Overall mental health

We focus on **correlation-based and visualization-based insights**. :

---

## 🛠️ Tech Stack & Python Concepts

**Languages & Libraries**

- Python
- `pandas` – data loading, cleaning, transformation
- `numpy` – numeric operations, handling missing values
- `matplotlib` – visualizations (bar, line, pie, etc.)

**Key Python concepts used** :

- Importing libraries: `pandas`, `numpy`, `matplotlib.pyplot`
- Reading CSV files: `pd.read_csv(...)`
- DataFrames for tabular data
- Removing duplicates: `drop_duplicates()`
- Custom cleaning function: `def clean_number(x): ...`
- `apply()` to clean entire columns
- Type conversion: `pd.to_numeric(..., errors="coerce")`
- Handling missing values (`NaN`)
- Filtering / selecting columns
- Calculating correlations: `Series.corr()`
- Conditional logic (`if/elif/else`) to interpret correlations

- **📈 Analysis Performed**

Main steps performed in the project:
Data Ingestion
Read the raw CSV file into a pandas DataFrame.
Data Cleaning
Removed duplicate rows.
Standardized column names.
Cleaned numeric fields using clean_number() function.
Converted data types to int / float where needed.
Handled missing values (NaN, blanks, "N/A", etc.).
Removed unrealistic outliers (e.g., screen time > 15 hours, sleep > 14 hours).

**Feature Understanding**
Focused on mental health related columns:
stress_level, anxiety_level, mood_level, sleep_hours_avg,
physical_activity, device_addiction_score, etc.

**Correlation Analysis**
Measured relationships such as:
Screen time vs anxiety/sleep
Physical activity vs mood
Used Pearson correlation via .corr().
Data Visualization
Bar charts
Line graphs
Pie charts / distributions
Visual interpretation of:
High vs low screen time groups
Sleep vs stress/anxiety
Platform usage patterns
Output
Cleaned dataset: social_media_health_clean.csv
Graphs and printed insights from the notebook.
- Exporting cleaned data: `df.to_csv(...)`
---
📌 **Key Findings / Interpretation**
From the cleaned dataset and visual analysis, the following patterns were observed:
High social media usage is associated with:
Higher stress and anxiety scores
Reduced sleep hours
Higher device addiction / eye strain
Lower mood and well-being
Low to moderate usage is associated with:
Better sleep quality
More stable mood
Improved balance between online time and real-life activity
Physical activity helps:
Acts as a positive stabilizer for mood and anxiety.

**Overall conclusion:**
Social media is not completely harmful, but excessive and unregulated use is clearly linked with worse mental health outcomes. Balanced use plus regular physical activity leads to better well-being.

🔮 **Possible Future Improvements**
Add a simple machine learning model to predict mental health status from usage patterns.
Collect a larger real-world dataset via surveys or APIs.
Compare results across age groups / platforms.
Automate report generation.

**Acknowledgements:**
Instructor / Guide: Prof. Madhuri Bhalekar
Dataset design and project guidance inspired by:
Pandas Documentation
NumPy Documentation
Matplotlib Documentation



