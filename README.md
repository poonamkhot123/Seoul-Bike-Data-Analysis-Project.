## **SeoulBike Data Analysis Project**  

### Objective
- Analyze the factors affecting bike rentals in Seoul.
- Understand patterns in bike usage over time and seasons.
- Visualize the impact of weather and time on rental demand.
- Provide insights to optimize bike rental operations.

###  Research Questions
- How does bike rental demand vary by time of day?
- What weather factors (temperature, humidity, etc.) affect rentals?
- Are there seasonal patterns in bike rentals?
- Do holidays impact bike rental demand?
- Can we predict rental demand based on weather and time?

### Dataset Overview
Data set = https://github.com/poonamkhot123/Seoul-Bike-Data-Analysis-Project./blob/d2f40d627ef516847afc49cbeb262908f9b0450b/SeoulBikeData%20(1).csv
- **Total Rows:** 8,760 (representing hourly data for a year)
- **Total Columns:** 14  
- **Important Features:**
  - `Rented Bike Count` → Target variable
  - `Hour` → Time of the day (0-23)
  - `Temperature(°C)`, `Humidity(%)`, `Wind speed (m/s)`, `Visibility (10m)`, `Solar Radiation (MJ/m2)`, `Rainfall(mm)`, `Snowfall (cm)` → Weather conditions
  - `Seasons` → Categorical (Winter, Spring, Summer, Autumn)
  - `Holiday`, `Functioning Day` → Whether it's a holiday or working day


 **Chart Type:** Histogram → Shows the distribution of bike rentals.
 **Chart Type:** Line Plot → Helps visualize hourly trends
 **Chart Type:** Box Plot → Shows seasonal variations.
 **Chart Type:** Scatter Plot → Shows the correlation between temperature and rentals.
 **Chart Type:** Heatmap → Identifies relationships between variables.

### Key Insights
- **Bike rentals peak in the morning (7-9 AM) and evening (5-8 PM).**
- **Higher temperatures lead to increased rentals, but extreme heat may reduce demand.**
- **Rainfall and snowfall negatively impact bike rentals.**
- **Winter has lower rentals, while summer has the highest.**
- **Holidays see fewer rentals compared to working days.**

### Tools & Technologies
- **Python Libraries:**
  - `pandas` → Data manipulation
  - `matplotlib` & `seaborn` → Data visualization
  - `numpy` → Numerical computations


### Conclusion & Recommendations
- **Conclusion:** 
  The analysis confirms that weather, time, and seasons impact bike rentals significantly.  
- **Recommendations:**
  - Increase bike availability during peak hours.
  - Offer promotions on holidays to boost rentals.
  - Optimize maintenance and stocking based on seasonal demand.

