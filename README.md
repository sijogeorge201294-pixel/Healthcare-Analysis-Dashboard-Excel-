# Healthcare-Analysis-Dashboard-Excel-
Developed an interactive Healthcare Analysis Dashboard using Microsoft Excel. The project demonstrates data analysis, data cleaning with Power Query, data modeling using Power Pivot, DAX calculations, Pivot Tables, and interactive dashboard creation. The dashboard enables users to analyze healthcare trends through KPIs, charts, and slicers.

## Tools Used 
Microsoft Excel	 :  Dashboard Development
Power Query	Data :  Cleaning & Transformation
Power Pivot	     :  Data Modeling
DAX	             :  Measures & Calculations
Pivot Tables     :  Data Summarization
Pivot Charts     :  Data Visualization
Slicers	         :  Interactive Filtering

## Objectives

1. Analyse the average healthcare charges across different age groups.
2. The number of surgeries based on transplant status.
3. Examine the relationship between smoking and cancer history.
4. Analyse patient distribution based on weight status and diabetes status. 
5. Compare average BMI and HbA1C across surgery counts. 
6. Provide interactive filtering using Cancer History, Diabetes Status, and Weight Status slicers.

## Steps Performed
Steps Involved in the Analysis

### 1. Data Import and Cleaning (Power Query) 
    Imported the Excel dataset into Power Query. 
    Cleaned the data by removing unnecessary columns. 
    Handled missing values and inconsistent records. 
    Performed data validation and formatting. 
    Loaded the transformed data into the Excel Data Model.

### 2. Data Modelling (Power Pivot) 
    Created relationships between the required tables. 
    Built calculated columns where necessary.
    Created DAX measures for key business metrics.

### 3. Data Analysis
    Created Pivot Tables based on the Data Model. 
    Used DAX measures within Pivot Tables for dynamic calculations. 
    Ensured all visuals respond to slicer selections.

### 4.Dashboard Development 
    Designed an interactive dashboard using Pivot Charts. 
    Added KPI cards for quick performance monitoring. 
    Included line charts, pie chart, clustered column chart, stacked bar chart, and heatmap. 
    Connected slicers to all relevant Pivot Tables and charts for interactive analysis. 
    Added dashboard formatting, icons, titles, and a dynamic "Last Updated" timestamp.

## Visualizations

### 1. Average Charges Across Age Groups 
    A line chart showing that average healthcare charges steadily increase with age, with patients above 60 years having the highest average charges.

### 2. Total Surgeries by Transplant Status
     A pie chart comparing patients with and without transplant history, showing that most surgeries were performed on patients without a transplant history.

### 3. Smoker Cancer Status
     A clustered column chart comparing smokers and non-smokers with respect to cancer history, helping identify the distribution of cancer cases among both
     groups.

### 4. Heart Patients by Surgery Count 
    A stacked bar chart displaying the number of heart patients categorized by surgery count and whether they have heart issues.

### 5. Patients Count by Weight & Diabetes Status 
    A heatmap highlighting patient distribution across different weight categories and diabetes status. Colour intensity makes it easy to identify combinations
    with higher patient counts.

### 6. Average BMI & HbA1C Across Surgery Patients 
    A line chart comparing average BMI and average HbA1C for patients based on the number of surgeries, helping observe changes in these health indicators.

 ### 7. Interactive Filters 
    Users can dynamically filter the dashboard using slicers for: • Cancer History • Diabetes Status • Weight Status

## Key Insights 

1. The average healthcare charges increase with age, with patients above 60 years showing the highest costs.
2. Most surgeries were performed on patients without a transplant history. 
3. Non-smokers represent the largest patient group, while cancer cases are comparatively lower than non-cancer cases. 
4. Obesity and normal weight categories contain the highest number of patients across diabetes groups.
5. Average BMI remains relatively stable across surgery counts, while HbA1C shows a slight increase among patients with more surgeries.
6. Interactive slicers allow users to analyse trends based on cancer history, diabetes status, and weight status.
