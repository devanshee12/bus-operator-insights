<img width="1052" height="565" alt="Screenshot 2025-09-05 at 9 16 23 AM" src="https://github.com/user-attachments/assets/c06f68c9-d0da-4011-afe0-d0a40429c429" /># bus-operator-insights
Data-driven analysis of Indian bus booking data — uncovering insights on pricing, travel duration, operator ratings, seat availability, and passenger experience using Python

📌 Overview

This project analyzes real-world bus travel booking data to extract insights into pricing, travel duration, operator ratings, seat availability, and passenger experience.
Using Python (Pandas, Matplotlib, Seaborn), I transformed raw CSV files into actionable business insights and visualized patterns that could help both passengers and operators optimize their decisions.

🎯 Objectives
	•	Clean and preprocess raw travel data for consistency.
	•	Convert string-based travel durations (e.g., "6h 30m") into numeric minutes for analysis.
	•	Perform Exploratory Data Analysis (EDA) to uncover trends in prices, ratings, and travel behavior.
	•	Visualize patterns in operator performance, seat availability, travel time, and ticket pricing.
	•	Provide data-driven insights useful for travelers, bus operators, and transport aggregators.

🗂 Dataset

Columns in the dataset:
	•	Operator – Bus operator name
	•	Departure Time – Scheduled departure
	•	Arrival Time – Scheduled arrival
	•	Travel Duration – Trip length (cleaned into minutes)
	•	Price – Ticket price (₹)
	•	Bus Type – Type of bus (AC/Non-AC, Sleeper, etc.)
	•	Seats Left – Remaining seats at time of query
	•	Window Seats – Window seats available
	•	Rating – Passenger ratings for operator
	•	Source – Starting city
	•	Destination – Destination city
	•	Distance – Distance of route (km)


🧹 Data Cleaning & Preprocessing
	•	Removed duplicates and invalid rows.
	•	Converted Travel Duration strings → numeric values in minutes.
	•	Handled missing/NULL values in ratings and seat availability.
	•	Normalized Price and Distance for consistent comparison.
	•	Prepared final cleaned dataset (cleaned_bus.csv).

 📊 Exploratory Data Analysis (EDA)

Key analyses performed:
	•	Price Distribution → Identified variation in ticket pricing across operators.
	•	Duration vs. Price → Explored relationship between travel time and fare.
	•	Ratings vs. Price → Checked if higher-rated operators charge premium fares.
	•	Seats Left vs. Window Seats → Measured demand indicators.
	•	Top 10 Operators → Ranked by average rating and price.

 📈 Visualizations (Python)

Created using Matplotlib & Seaborn:
	•	Histogram of Price Distribution
	•	Boxplot of Price vs. Operator
	•	Scatterplot of Price vs. Ratings
	•	Bar chart of Top 10 Operators (by rating, avg price)
	•	Line chart of Departure Time vs. Price Trends

💡 Insights Generated
	•	Operators with higher ratings don’t always have the highest fares, revealing opportunities for cost-conscious travelers.
	•	Longer travel durations strongly correlate with higher ticket prices, but outliers exist.
	•	Certain departure times (late night / early morning) consistently offer lower prices.
	•	Window seats fill up faster → indicator of high passenger preference.
	•	Price variation across operators suggests market segmentation strategies.

 🛠 Tech Stack
	•	Python: Data cleaning, preprocessing, EDA, visualization
	•	Pandas: Data manipulation
	•	Matplotlib & Seaborn: Data visualization
	•	NumPy: Numerical operations
	•	Jupyter Notebook / Google Colab: Development environment

 📦 bus-travel-analytics
 ┣ 📜 cleaned_bus.csv        # Cleaned dataset
 ┣ 📜 bus_analysis.ipynb     # Full analysis notebook
 ┣ 📜 requirements.txt       # Dependencies
 ┣ 📜 README.md              # Project documentation

 🚀 Future Improvements
	•	Expand dataset with real-time API data (e.g., RedBus, state transport).
	•	Predict ticket price fluctuations using ML models.
	•	Build an interactive dashboard (Streamlit / Dash).
	•	Compare AC vs. Non-AC buses pricing trends.

 📌 Key Takeaway

This project demonstrates my ability to:
✔️ Clean and preprocess messy real-world data
✔️ Perform end-to-end data analysis in Python
✔️ Create compelling data visualizations for business insights
✔️ Extract actionable insights relevant to both customers & businesses


<img width="393" height="221" alt="Screenshot 2025-09-05 at 7 52 43 AM" src="https://github.com/user-attachments/assets/a87d7057-a598-423b-a728-297752cdba06" />
<img width="394" height="441" alt="Screenshot 2025-09-05 at 8 54 21 AM" src="https://github.com/user-attachments/assets/52f97e69-cd13-4d8f-9cda-fca0cbf8f53b" />
<img width="572" height="234" alt="Screenshot 2025-09-05 at 8 55 12 AM" src="https://github.com/user-attachments/assets/ec7004de-6429-4b92-8658-5125d71d5457" />
<img width="625" height="285" alt="Screenshot 2025-09-05 at 8 55 46 AM" src="https://github.com/user-attachments/assets/4cc13852-466f-4b12-bab4-6c7c26fcf219" />
![Uploading Screenshot 2025-09-05 at 9.<img width="1260" height="560" alt="Screenshot 2025-09-05 at 9 14 28 AM" src="https://github.com/user-attachments/assets/9151e752-7d03-4d7f-bb36-376ee6e1b7ac" />
<img width="904" height="556" alt="Screenshot 2025-09-05 at 9 15 01 AM" src="https://github.com/user-attachments/assets/caa61214-b67f-43b4-ad8a-f13857e76ae9" />
<img width="1172" height="566" alt="Screenshot 2025-09-05 at 9 15 28 AM" src="https://github.com/user-attachments/assets/fb472636-08fd-4bdd-9fa4-9a30ffb99b5f" />
<img width="872" height="566" alt="Screenshot 2025-09-05 at 9 15 47 AM" src="https://github.com/user-attachments/assets/ded3d72b-c2fc-4cb9-a037-5d7ee733e719" />
<img width="872" height="566" alt="Screenshot 2025-09-05 at 9 16 05 AM" src="https://github.com/user-attachments/assets/5ee0a46a-5542-4dfc-a046-f64757140412" />
16.23 AM.png…]()



