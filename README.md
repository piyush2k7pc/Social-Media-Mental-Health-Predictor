# 🌐 Social Media Mental Health Predictor

This project analyzes how **social media usage patterns** such as screen time and platform usage affect **mental health indicators** including stress, anxiety, mood, and sleep.

Using Python, the data is cleaned, visualized, and interpreted to extract meaningful patterns.  
Additionally, an **interactive web dashboard** is developed to evaluate personal digital habits and predict health scores.

---

## 📌 Project Overview

- Clean and analyze a dataset containing social media habits and health data  
- Explore correlations between behavior and mental well-being  
- Build visualizations to reveal trends  
- Develop a **predictive dashboard interface** where users input data to get:
  - Stress level prediction  
  - Anxiety level prediction  
  - Eye strain prediction  
  - Lifestyle assessment  
  - Doctor recommendations  
  - Final health status  

---

## 🗂️ Dataset Overview

The dataset contains **self-reported metrics** on:

- Daily screen time  
- Sleep duration  
- Stress and anxiety levels  
- Physical activity  
- Mood  
- Social interaction  
- Social media platform usage  
- Academic performance  
- Device addiction score  

### 📁 Files Used

- `social_media_health_extended_big.csv` – Raw dataset  
- `social_media_health_clean.csv` – Cleaned dataset  

---

## 🧠 Problem Statement

With increasing dependency on social media, especially among youth, its effects on mental health have become a concern.

This project investigates how different patterns of behavior correlate with:

- Stress  
- Anxiety  
- Mood  
- Sleep quality  
- Overall well-being  

The analysis is **correlation-driven and visualization-based**.

---

## 🛠️ Tech Stack

### 🧾 Libraries

- Python  
- `pandas`  
- `numpy`  
- `matplotlib`  

### ⚙️ Concepts Used

- DataFrame operations  
- Missing value handling  
- Type conversion  
- Duplicate removal  
- Outlier detection  
- Function applications  
- Correlation calculations  
- Plot visualizations  

---

## 📊 Data Analysis Workflow

### 1. 📥 Data Ingestion
- Load raw CSV using `pandas`

### 2. 🧹 Cleaning
- Drop duplicates  
- Standardize column names  
- Convert types to numeric  
- Handle missing values  
- Remove unrealistic outliers  

### 3. 🔍 Feature Understanding
Focus on mental health attributes:

- `stress_level`  
- `anxiety_level`  
- `mood_level`  
- `sleep_hours_avg`  
- `physical_activity`  
- `device_addiction_score`  

### 4. 📈 Correlation Analysis

Relationships studied:

- Screen time ↔ Anxiety/Sleep  
- Physical activity ↔ Mood  

Uses **Pearson correlation**.

### 5. 📉 Visualization

Examples of charts produced:

- Bar chart of happiness by age  
- Histogram of daily social media use  
- Primary platform distribution (pie chart)  
- Scatterplot of screen time vs anxiety  

### 6. 📦 Output

- Cleaned dataset  
- Statistical summaries  
- Insightful charts  

---

## 🧪 Key Visual Insights

> Higher social media usage is linked with increased stress and anxiety.

> Low sleep and high device addiction were common in high-usage groups.

> Moderate screen time + physical activity → more stable mood and sleep.

---

## 🔑 Key Findings

### 🚨 High usage correlates with:
- Elevated stress & anxiety  
- Lower sleep  
- High device strain  
- Worse mood  

### 🟢 Moderate usage correlates with:
- Better sleep  
- More stable mental health  

### 🏃 Physical activity acts as:
- A **protective factor** against stress & anxiety  

### ✔️ Conclusion

Social media is not inherently harmful, **but excessive, unregulated use negatively affects mental health**.  
Balanced usage + healthier habits → improved well-being.

---

## 🌐 Interactive Web Dashboard (New Feature)

A fully functional **HTML + JavaScript dashboard** was developed to allow users to:

- Enter daily screen time, sleep, social usage, stress, anxiety  
- Get predicted scores for:
  - Stress  
  - Anxiety  
  - Eye strain  
- Receive lifestyle advice  
- Receive doctor recommendations  
- See final health evaluation  

The dashboard includes:

- Modern card-based UI  
- Input validation  
- Animated result display  
- Detailed recommendations  

> The dashboard UI is defined in the HTML file included in the project files.

### 🖼️ Embedded Visual Data Insights

Four visualizations are embedded into the dashboard:

- Bar chart  
- Histogram  
- Pie chart  
- Scatter plot  

This makes the interface both **analytical and user-friendly**.

---

## 🚀 Possible Future Enhancements

- Train a machine learning model for prediction  
- Deploy the dashboard using Flask or FastAPI  
- Collect larger survey data  
- Add user authentication  
- Convert UI into a mobile app  

---

## 🙏 Acknowledgements

- Instructor / Guide: **Prof. Madhuri Bhalekar**  
- Tools used: Pandas, NumPy, Matplotlib  
- UI inspired and structured via prototyping and documentation

---

## 📜 License

This project is intended for **academic and research purposes**.  
You may build upon it with proper citation.

---
