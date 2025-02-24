**Title:** Forecasting Energy Usage Consumption for eSC Energy Company  
**Course:** IST 687 – Introduction to Data Science  
**Team Members:** Harish Reddy Yeddula, Kunal Jain, Nikitha Chandana, Raghuveera Narasimha, Rishi Siddanth Yaga  

#### **Project Overview**
This project aimed to develop a predictive model to forecast energy consumption for eSC Energy Company, addressing potential blackouts and unnecessary infrastructure expansion due to global warming-induced demand spikes. The focus was on energy usage in July, with an additional analysis simulating a 5-degree Celsius temperature rise.

#### **Key Steps:**
1. **Data Merging** – Combined static house data, energy usage, and weather data using dynamic retrieval and error handling.
2. **Data Summarization** – Aggregated data at a daily level for better analysis.
3. **Data Cleaning** – Managed missing values, removed redundant data, and created new classifications.
4. **Data Exploration** – Visualized consumption patterns using bar charts, heatmaps, and box plots.
5. **Predictive Modeling** – Developed a linear regression model to predict energy usage.
6. **Impact of Warmer Temperatures** – Simulated a scenario with a 5-degree increase in temperature to predict energy demand.
7. **Visualization & Insights** – Created dashboards to analyze correlations between building characteristics, weather, and energy usage.
8. **Shiny Application** – Developed an interactive tool for energy consumption exploration.
9. **Recommendations** – Proposed strategies to optimize energy consumption.
10. **Conclusion** – Demonstrated how data science can support energy efficiency and sustainability.

---

### **README**
#### **Project Name:** Forecasting Energy Usage Consumption for eSC Energy Company  
#### **Description:**  
This project focuses on predicting energy demand for eSC Energy Company to optimize energy consumption and prevent overloads. It involves data merging, cleaning, exploration, modeling, and visualization using R and Shiny dashboards.

#### **Installation & Dependencies:**  
Ensure you have the following libraries installed in R:  
- `arrow`  
- `dplyr`  
- `ggplot2`  
- `caret`  
- `shiny`  

#### **How to Run the Project:**  
1. **Data Preparation:**  
   - Download datasets from Amazon S3 (static house info, energy, and weather data).  
   - Merge and clean the data.  

2. **Exploratory Data Analysis:**  
   - Run the scripts to generate visualizations of energy usage trends.  

3. **Predictive Modeling:**  
   - Train a linear regression model on cleaned data.  
   - Evaluate the model using RMSE, MAE, and R-squared metrics.  

4. **Simulating Future Energy Demand:**  
   - Modify the dataset to simulate a 5°C increase in temperature.  
   - Re-run the model to forecast future energy consumption.  

5. **Shiny Dashboard:**  
   - Launch `shinyApp(ui, server)` to explore interactive visualizations.  

#### **Key Insights & Recommendations:**  
- Energy usage varies significantly with building materials, size, and external temperatures.  
- Large buildings and certain materials (e.g., wood frame) consume more energy.  
- Policy changes should focus on high-consumption cities and encourage renewable energy adoption.  
- Implement predictive maintenance and behavioral interventions for energy savings.  

#### **Authors:**  
Harish Reddy Yeddula, Kunal Jain, Nikitha Chandana, Raghuveera Narasimha, Rishi Siddanth Yaga  

#### **License:**  
Open for academic and research purposes.  

