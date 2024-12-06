# OnlineCoursesPlatFormAnalysis-Using-Python
Online Education Platform Analysis Using Python
Introduction
This project provides a data-driven comparison of Udemy and Coursera to help users choose the best platform for their educational goals. Key factors analyzed include course variety, enrolment patterns, instructor quality, pricing, and certificate credibility.

Methodology
1. Data Collection
Source: Kaggle datasets for Udemy and Coursera courses.
Key Attributes:
Course Category, Name, Duration (hrs), Enrolments
Free vs. Paid, Price ($), Level, Rating, Reviews
2. Data Cleaning
Handle missing/duplicate values.
Standardize numerical and categorical data.
3. Metrics for Analysis
Weighted Average Rating: Gives more weight to courses with higher reviews.
Insights Generated:
Course enrolment patterns (Category, Level, Free vs. Paid).
Pricing trends and rating correlations.
Popular courses via Word Cloud.
Key Insights
Course Enrolment:
Patterns by Category, Level, Free vs. Paid.
Popularity:
Reviews vs. Ratings, Popular Courses visualization.
Pricing:
Trends in pricing and enrolments.
Platform comparison for free vs. paid courses.
Duration:
Correlation between course duration and ratings.
Tools and Libraries
Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn, WordCloud
Steps to Run
Install Dependencies:
bash
Copy code
pip install pandas numpy matplotlib seaborn wordcloud
Load Dataset: Download Kaggle data and place it in data/.
Run Analysis: Open and execute analysis.ipynb.
Outcomes
Platform comparison with actionable insights.
Data-driven recommendations for learners.

