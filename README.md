# Uber Ride Demand Analysis Project

## Project Overview
This project analyzes Uber ride data to understand usage patterns, peak hours, popular locations, and trip durations. Insights are visualized using Python and a Power BI dashboard to support data-driven decisions.

## Files in the Project
- **UberDataset.csv** – Original raw Uber ride dataset.  
- **UberDatasetCleaned.csv** – Cleaned dataset after preprocessing.  
- **uber.ipynb** – Python Jupyter notebook containing the data analysis.  
- **Uber.pbix** – Power BI dashboard file.  
- **Dashboard.png** – Screenshot of the dashboard.  
- **Uber_Rides_Data_Analysis_Documentation_and_Recommendations.docx** – Detailed documentation and recommendations.  
- **requirements.txt** – Python libraries required to run the notebook.  

## Analysis Steps
1. Imported libraries: Pandas, NumPy, Matplotlib, Seaborn for data manipulation and visualization.  
2. Loaded datasets and explored their structure.  
3. Handled missing values and converted date/time columns to appropriate formats.  
4. Extracted new features like month, day, hour, and trip duration.  
5. Visualized data patterns using count plots, heatmaps, bar charts, and distribution plots.  
6. Saved the cleaned dataset for dashboard visualization.

## Dashboard Insights
- Distribution of rides by category (business vs personal).  
- Monthly ride counts and total miles traveled.  
- Day-of-week ride patterns.  
- Ride purpose analysis by category.  
- Trip distance analysis by time of day.

## Recommendations
1. Optimize ride allocation during peak months.  
2. Target marketing campaigns by ride purpose.  
3. Improve services during peak hours.  
4. Monitor and reduce trip durations.  
5. Enhance services in high-demand categories.  
6. Seasonal promotions and special offers.  
7. Analyze high-mileage trips for efficiency.  
8. Focus on popular routes and destinations.  
9. Integrate customer feedback for better service.  
10. Conduct driver training programs to improve service quality.  

## How to Use This Project
1. Load the CSV files into a pandas DataFrame.  
2. Run the Jupyter notebook (`uber.ipynb`) to explore data cleaning and analysis.  
3. Open `Uber.pbix` in Power BI to view the dashboard.  
4. Review recommendations in the documentation file.

## Clone the Repository
```bash
git clone https://github.com/HrutikaSawant/Uber-Ride-Demand-Analysis.git
cd Uber-Ride-Demand-Analysis
pip install -r requirements.txt
jupyter notebook uber.ipynb
