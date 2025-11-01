# Exploratory-Data-Analysis-for-MetroMove-Transit-Using-Python
This repository contains an end-to-end exploratory data analysis on a simulated public transportation dataset (buses, trains, ferries, trams). The goal was to clean the data, engineer time-based features, and uncover patterns that can help a transit agency improve passenger experience and revenue.

Key things in this repo:

🔧 Data cleaning: removed empty columns, fixed casing/whitespace, handled missing numeric values with median.

🕒 Feature engineering: extracted hour, day of week, time of day, revenue, and route (Departure → Arrival).

📊 Univariate / bivariate analysis: distribution of passengers, fares, trip duration, and revenue.

🚍 Transport performance: BUS is the top mode by trips, passengers, and revenue; TRAM has the highest passengers per trip.

🗓️ Demand patterns: Thursdays and weekdays are busier; mornings and afternoons have the most trips.

🗺️ Top routes/stations: “North Station → Downtown” and “Central” station generate the highest volumes.

💰 Revenue insight: revenue correlates more with passenger volume and fare than with trip duration.

📈 Visuals: heatmaps, bar charts, boxplots, and time-of-day views (all in blue palette for consistency).


Use this project as a reference for:

building a clean EDA notebook,

telling a business story from transport data,

and creating portfolio-ready visuals.
