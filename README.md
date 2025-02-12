# british-airways-dashboard
📊 Analyzing 1,324 British Airways customer reviews to uncover trends in passenger satisfaction, service quality, and travel experience. This interactive Tableau dashboard visualizes key insights across multiple dimensions, including ratings, geospatial trends, and time-series analysis.
🚀 Project Overview

This project leverages Tableau to analyze customer reviews of British Airways. The dashboard helps identify:
✅ Sentiment trends based on ratings for seat comfort, entertainment, food, and staff service.
✅ Geospatial insights, mapping review distribution by countries and regions.
✅ Time-series analysis of airline performance across different months.
✅ Key performance indicators (KPIs) for evaluating overall customer satisfaction.

🔹 Live Dashboard: [Your Tableau Public Link (if applicable)]
📂 Dataset Information
File Name	Description
ba_reviews.csv	Contains 1,324 airline reviews with ratings for various services.
Countries.csv	Country mapping dataset to analyze customer location trends.
BritishAirways.twb	Tableau workbook file with visualizations.

🔹 Data Cleaning & Preparation:

    Replaced negative (-1) values in ratings with NULL.
    Converted date_flown and date into proper datetime format.
    Mapped countries using ISO country codes for accurate geospatial representation.

📊 Dashboard Insights
1️⃣ Sentiment Analysis

    Breakdown of passenger satisfaction across different services (seat comfort, entertainment, food).
    KPI visualization showing "Recommended" vs. "Not Recommended" customer trends.

2️⃣ Geospatial Trends

    Mapped customer reviews by country to see which regions have the best or worst feedback.
    Integrated country codes from Countries.csv for location-based analysis.

3️⃣ Time-Series Analysis

    Monthly trends in airline ratings, identifying seasonal fluctuations.
    Helps airline management understand when service ratings drop or improve.

🛠 Tools & Technologies Used

✅ Tableau – For data visualization & dashboard creation.
✅ SQL (optional) – Used for data cleaning and preprocessing.
✅ Excel / Power Query – For initial data wrangling.
📌 How to Use

    Download the repository or clone it:

git clone https://github.com/yourusername/airline-review-analysis.git

Open BritishAirways.twb in Tableau.
Ensure ba_reviews.csv and Countries.csv are correctly linked in the data source.
Explore the interactive dashboard to gain insights
