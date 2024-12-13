# Cooking Sessions and User Behavior Analysis

This repository contains an exploratory data analysis (EDA) project aimed at understanding the relationship between cooking sessions and user orders, identifying popular dishes, and exploring demographic factors influencing user behavior. The project also includes data visualizations and business recommendations based on the findings.

## Project Overview
This project involves:

1. Cleaning and merging raw data from various sources.
2. Analyzing relationships between cooking sessions and user orders.
3. Identifying the most popular dishes and meal types.
4. Exploring the impact of demographic factors such as age and location on user behavior.
5. Creating visualizations to highlight key insights.
6. Summarizing findings and providing actionable business recommendations.

## Dataset
The dataset used in this project includes the following columns after cleaning:

- **Session Information**: `Session ID`, `Session Start`, `Session End`, `Duration (mins)`, `Session Rating`, `Session Day`, `Session Hour`
- **User Information**: `User ID`, `Age`, `Location`, `Registration Date`, `Favorite Meal`, `Total Orders`
- **Order Information**: `Order ID`, `Order Date`, `Order Status`, `Amount (USD)`, `Revenue per Session`, `Order Success`
- **Dish Details**: `Dish Name`, `Meal Type`

## Key Insights
- **Popular Dishes**:
  - Spaghetti and Grilled Chicken are the most ordered dishes.
  - Dinner is the most popular meal type.

- **Demographic Analysis**:
  - Users aged 28, 35, and 42 placed the highest number of orders.
  - Locations like Chicago, Los Angeles, and New York show the highest order activity.

- **Cooking Sessions vs. Orders**:
  - Higher session ratings correlate with increased order success.
  - Sessions conducted on weekends (Sunday) generate the most revenue.

## Visualizations
All visualizations are saved in the `visualizations/` folder and include:

1. **Top 10 Most Popular Dishes**: `Top_10_Most_Popular_Dishes.png`
2. **Meal Type Distribution**: `Meal_Type_Distribution.png`
3. **Order Count by Age**: `Order_Count_by_Age.png`
4. **Revenue per Session Day**: `Total Revenue per Session Day.png`
5. **Successful Orders per Session Day**: `Revenue_Successful_Orders_by_Day.png`

## Recommendations
1. **Optimize Popular Dishes**: Focus on promoting and improving Spaghetti and Grilled Chicken.
2. **Leverage Demographics**: Target users aged 28-42 and key locations like Chicago and Los Angeles with personalized offers.
3. **Weekend Promotions**: Introduce exclusive offers for weekend sessions to maximize revenue.
4. **Enhance User Experience**: Improve session ratings to boost order success.

## Repository Structure
```
├── data/
│   ├── raw_data.csv
│   ├── cleaned_data.csv
├── visualizations/
│   ├── Top_10_Most_Popular_Dishes.png
│   ├── Meal_Type_Distribution.png
│   ├── Order_Count_by_Age.png
│   ├── Order_Count_by_Location.png
│   ├── Revenue_Successful_Orders_by_Day.png
├── notebooks and report
│   ├── EDA.ipynb
│   ├── final_report.docx 
├── README.md
```

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub for version control

## Acknowledgments
We thank the team for providing the data and support for this analysis.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
