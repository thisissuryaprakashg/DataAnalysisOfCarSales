# Car Sales Data Analysis 🚗📊  

This project is an **Exploratory Data Analysis (EDA) and Visualization** of car sales data using Python. The goal is to analyze trends in car sales, understand relationships between different vehicle attributes, and provide insights into the automotive industry through interactive data visualizations.  

## 📌 Features  
✅ **Data Cleaning & Preprocessing**  
   - Reads raw car sales data from `datalists.csv`.  
   - Handles missing values, removes duplicates, and reformats certain fields.  
   - Saves the cleaned data as `output.csv`.  

✅ **Statistical Analysis**  
   - Computes **Mean, Median, and Mode** for:  
     - Sales in thousands  
     - Power performance factor  
     - Year resale value  
   - Displays the computed statistics interactively using Tkinter.  

✅ **Graphical Analysis**  
   - Uses **Seaborn and Matplotlib** to generate insightful plots:  
     - **Bar Plots:** Manufacturer-wise sales, fuel capacity, and resale value comparisons.  
     - **Scatter Plots:** Relationship between horsepower and price.  
     - **Box Plots:** Variability of resale value across different vehicle types.  
     - **Heatmaps:** Correlation analysis between various numerical attributes.  

✅ **Hierarchical Dropdown Interface**  
   - Users can select different analysis types (e.g., Mean, Median, Mode) and visualization types (e.g., Bar, Box, Scatter plots) via a **dropdown menu**.  

✅ **Full-Screen GUI Application**  
   - Built using **Tkinter**, with easy navigation between different analysis sections.  
   - Includes buttons for displaying raw & cleaned data, statistical measures, and graphs.  

## 📊 Key Analyses  
- **Sales Trends**: Identifying manufacturers with the highest sales.  
- **Pricing Analysis**: Correlation between horsepower and price.  
- **Resale Value**: Understanding how vehicle type affects resale value.  
- **Fuel Capacity**: Comparing fuel capacities across manufacturers.  
- **Heatmap Analysis**: Identifying correlations between numerical attributes.  

## 🛠️ Technologies Used  
- **Python** 🐍  
- **Pandas** (Data Manipulation)  
- **Matplotlib & Seaborn** (Data Visualization)  
- **Tkinter** (GUI Development)  
