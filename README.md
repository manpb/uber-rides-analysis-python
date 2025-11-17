🚕 Uber Rides Data Analysis – New York (2016)
📌 Project Overview

This project analyzes 1,155 Uber rides recorded throughout 2016 in New York.
The dataset includes trip start/end timestamps, locations, distances traveled, and trip purposes.
The objective is to uncover insights into business mobility patterns and identify opportunities to improve operational efficiency and reduce travel costs.

🎯 Key Questions

What is the primary use of Uber in this dataset?

When are the busiest travel periods?

Which locations and routes show the highest demand?

Are there any anomalies or outliers in trip distances?

How can organizations optimize corporate travel costs?

🧹 Data Preprocessing

Steps performed:

Removed invalid/missing timestamp and location values

Converted date fields to proper datetime format

Filled missing trip purposes (Unknown)

Created new features:

Hour, Day, Month, Weekday

Trip Duration

Standardized columns for analysis

🔎 Exploratory Data Analysis — Summary of Findings
🚀 Business Usage Dominates

93% of rides are for Business purposes

94% of total miles (11,487 mi) are business-related
➡ Indicates heavy corporate reliance on Uber for operational mobility

🎯 Trip Purpose Distribution

Meetings, Meal/Entertainment, and Errands/Supplies are top known purposes

43% missing purpose labels → opportunity to improve data logging

⏱️ Travel Timing Behavior

Friday is the busiest day with ~209 trips

Peak hours: 11 AM – 2 PM → midday business commutes

Very limited late-night travel → not leisure-oriented usage

🗺️ Location Insights

Most trips originate from Cary, Morrisville, and Whitebridge

Several Unknown locations indicate input quality issues

🚘 Distance Patterns

Mostly short urban travel (<20 miles)

Several long-distance outliers 200–300+ miles

Likely airport or inter-city travel

Flagged for potential policy review

🧠 Business Implications
Area	Insight	Recommended Action
Demand Management	High Friday midday demand	Optimize fleet availability & driver scheduling
Corporate Cost Efficiency	Surge pricing likely at peak times	Encourage virtual meetings / ride sharing
Data Governance	Missing trip purposes	Enforce mandatory input fields
Geographical Strategy	High demand around Cary, Morrisville	Prioritize driver coverage in these hubs
Outlier Monitoring	Very long trips	Review for policy compliance
📈 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook (VS Code)

📂 Repository Structure
📦 Uber-Rides-Analysis-2016
 ┣ 📁 notebooks
 ┃ ┗ 📄 uber_rides_analysis_2016.ipynb
 ┣ 📁 data
 ┃ ┗ 📄 README.md   ← Contains link to download the dataset from Kaggle
 ┣ 📄 README.md     ← Project documentation (this file)


🚀 Future Enhancements

Add geospatial visualizations (Folium/Plotly)

Build interactive dashboard with Streamlit or Power BI

Integrate cost estimation per trip for financial analysis

Improve location standardization and purpose categorization

🙌 Acknowledgements

Dataset source: Kaggle — Uber Drives Dataset (2016)
Analysis & insights by: Manuja Palamakumbura

🔗 Project Webpage

You can view this project in my portfolio web site feature here:
👉 https://www.manujasprojects.co.uk/
