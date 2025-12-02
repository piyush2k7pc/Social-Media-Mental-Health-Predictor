Social Media Mental Health Predictor
📌 Overview

This project analyzes how social media usage patterns (screen time, platform usage, etc.) affect mental health indicators such as stress, anxiety, mood, and sleep.
Using Python, we clean a real-world style dataset, perform exploratory data analysis (EDA), compute correlations, and visualize patterns to understand the relationship between social media and mental well-being.

🎯 Project Objectives

Analyze the impact of social media usage on mental health

Identify key negative factors such as high screen time and low sleep

Explore both positive and negative effects of social media

Use Python data analysis tools to clean, transform, and visualize the dataset

Present insights clearly for academic / research purposes

📊 Dataset Overview

We primarily work with a CSV dataset containing self-reported metrics on social media usage and health.

Key Columns

user_id – Unique participant ID

age – Age of the participant

gender – Gender category

daily_screen_time – Total hours on social media per day

screen_time_before_sleep – Phone usage (hours) before sleep

platform_used_most – Most used app (Instagram, WhatsApp, etc.)

stress_level (1–10)

anxiety_level (1–10)

sleep_hours_avg – Average sleep per day (hours)

mood_level (1–10)

physical_activity – Daily exercise (minutes)

academic_performance – Percentage score

social_interaction_real_life – Frequency of offline interaction

device_addiction_score

comments_or_posts_per_day

mental_health_status – Overall label (Good / Moderate / Poor)

Files Used

social_media_health_extended_big.csv – Raw / extended dataset

social_media_health_clean.csv – Cleaned dataset after preprocessing

🧠 Problem Statement

With the rapid rise of social media usage, especially among students and young adults, there is growing concern about its impact on mental health.

This project uses structured data + Python to study how different levels of social media usage relate to:

Stress

Anxiety

Mood

Sleep quality

Overall mental health

We focus on correlation-based and visualization-based insights.

🛠️ Tech Stack & Python Concepts
Languages & Libraries

Python

pandas – data loading, cleaning, transformation

numpy – numeric operations, handling missing values

matplotlib – visualizations

Key Python Concepts Used

Importing libraries (pandas, numpy, matplotlib.pyplot)

Reading CSV files (pd.read_csv(...))

DataFrames for tabular data

Removing duplicates (drop_duplicates())

Custom cleaning function (def clean_number(x): ...)

Applying functions to columns (apply())

Type conversion (pd.to_numeric(..., errors="coerce"))

Handling missing values (NaN, blanks, "N/A", etc.)

Filtering / selecting columns

Calculating correlations (Series.corr())

Conditional logic (if/elif/else) for interpretation

Exporting cleaned data (df.to_csv(...))

📈 Analysis Performed
1. Data Ingestion

Read the raw CSV file into a pandas DataFrame

2. Data Cleaning

Removed duplicate rows

Standardized column names

Cleaned numeric fields using clean_number()

Converted data types to int / float where needed

Handled missing values (NaN, blanks, "N/A", etc.)

Removed unrealistic outliers (e.g., screen time > 15 hours, sleep > 14 hours)

3. Feature Understanding

Focused on mental health related columns:

stress_level, anxiety_level, mood_level, sleep_hours_avg,

physical_activity, device_addiction_score, etc.

4. Correlation Analysis

Measured relationships such as:

Screen time vs. anxiety / sleep

Physical activity vs. mood

Used Pearson correlation via .corr().

5. Data Visualization

Generated visualizations such as:

Bar charts

Line graphs

Pie charts / distributions

Interpreted:

High vs. low screen time groups

Sleep vs. stress / anxiety

Platform usage patterns

6. Output

Cleaned dataset: social_media_health_clean.csv

Graphs and printed insights from the notebook

📌 Key Findings / Interpretation
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

Acts as a positive stabilizer for mood and anxiety

Overall Conclusion:
Social media is not completely harmful, but excessive and unregulated use is clearly linked with worse mental health outcomes.
Balanced usage plus regular physical activity leads to better well-being.

🔮 Possible Future Improvements

Add a simple machine learning model to predict mental health status

Collect a larger real-world dataset via surveys or APIs

Compare results across age groups / platforms

Automate report generation

🙏 Acknowledgements

Instructor / Guide: Prof. Madhuri Bhalekar

Dataset design and project guidance inspired by official documentation of:

Pandas

NumPy

Matplotlib

📄 License

This project is intended for academic and research purposes.
You may modify or build upon it with proper citation.
