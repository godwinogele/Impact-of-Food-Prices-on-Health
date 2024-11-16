# Impact-of-Food-Prices-on-Health


### **Project Overview**  
This repository contains the complete analysis and visualization project titled **"The Impact of Food Prices on Health."** The project explores how food prices affect health outcomes in **Nigeria** and **Niger**, focusing on affordability, nutrition, and economic factors. Using **Power BI**, this project presents insights through interactive visualizations and key metrics.  

---

### **Contents of the Repository**  

1. **Datasets:**  
   - `daily cost of healthy diet per person.csv`  
   - `monthly change in food price over the years.csv`  
   - `share of pop that cannot afford healthy diet.csv`  
   - `share of pop that is undernourished.csv`  
   - `share-employment-agriculture-industry-services.csv`  

   These datasets were used for analysis and visualization.  

2. **Power BI File:**  
   - `Impact_of_Food_Prices.pbix`  
     Contains the Power BI dashboard with three key visuals:  
     - Doughnut Chart: **Employment Distribution**  
     - Clustered Bar Chart: **Comparison of Health and Affordability Metrics by Country**  
     - Line Chart: **Average Cost of Healthy Food Across Various Years**  

3. **DAX Formulas:**  
   - All DAX calculations used for KPIs are documented in the README file and implemented in the Power BI file.  

4. **Documentation:**  
   - `Project_Documentation.md`: Detailed project documentation including background, methodology, findings, and recommendations.  
   - `README.md`: This file provides an overview of the project and instructions for using the repository.  

5. **Screenshots:**  
   - Contains PNG files of the dashboard for preview purposes.  

---

### **Key Metrics and Findings**  

#### **KPIs (Key Performance Indicators):**  
1. **Population Unable to Afford Diet (%):** **91.75%**  
2. **Avg. Daily Cost of Healthy Diet (USD):** **3.40 USD**  
3. **Undernourishment Rate (%):** **12.73%**  
4. **Food Price Index (CFPI):** **-0.06**  

#### **Visualizations in Power BI:**  
1. **Doughnut Chart:** Employment distribution by sector (Agriculture, Industry, Services).  
2. **Clustered Bar Chart:** Comparison of health and affordability metrics between Nigeria and Niger.  
3. **Line Chart:** Trend of the average daily cost of a healthy diet over various years for both countries.  

---

### **DAX Formulas Used**  
1. **AvgUnaffordablePopulation:**  
   ```DAX
   AvgUnaffordablePopulation = AVERAGE('share of pop that cannot afford'[Share of the population who cannot afford a healthy diet])
   ```  

2. **AvgDailyCost:**  
   ```DAX
   AvgDailyCost = AVERAGE('daily cost of healthy diet per'[Cost of a healthy diet])
   ```  

3. **AvgUndernourished:**  
   ```DAX
   AvgUndernourished = AVERAGE('share of pop that is undernouri'[Prevalence of undernourishment (%)])
   ```  

4. **AvgCFPI:**  
   ```DAX
   AvgCFPI = AVERAGE('monthly change in food price ov'[IFPA_By_CFPI])
   ```  

---

### **How to Use the Repository**  

1. **Clone the Repository:**  
   Clone this repository to your local machine using:  
   ```bash
   git clone https://github.com/yourusername/Impact-of-Food-Prices-on-Health.git
   ```  

2. **Open the Power BI File:**  
   Download and open the `.pbix` file using Power BI Desktop.  

3. **View and Explore:**  
   - Interact with the visuals on the dashboard.  
   - Use slicers to filter by year or country.  

4. **Modify or Extend:**  
   - Replace datasets or add new fields for further analysis.  

---

### **Findings and Recommendations**  

**Findings:**  
1. **High Inaccessibility:** Over 91% of the population in Nigeria and Niger cannot afford a healthy diet.  
2. **Rising Costs:** The average daily cost of a healthy diet is $3.40 USD, which exceeds the affordability range for most people.  
3. **Public Health Concern:** Undernourishment affects 12.73% of the population.  

**Recommendations:**  
1. Introduce food subsidies for essential items to improve affordability.  
2. Strengthen employment policies to boost income levels.  
3. Develop education campaigns focused on affordable nutrition and diet choices.
