# Life-Expectancy-Analysis-Using-Python


##  Overview
This project explores **global life expectancy trends** from **2000 to 2015**, analyzing how health, economic, and social factors influence human longevity.  
By using data-driven insights and visualization techniques, the analysis identifies key patterns, correlations, and disparities across different continents.

---

##  Objective
The main goal of this project is to **understand the major factors affecting life expectancy** and provide actionable insights for improving global health outcomes.  

### Specific objectives include:
- Identifying **health, economic, and social indicators** strongly correlated with life expectancy.  
- Examining **regional differences** and understanding why disparities exist.  
- Evaluating the impact of **preventable diseases** and **healthcare investment** on longevity.  
- Providing **recommendations** for policymakers and researchers.

---

##  Dataset
- **Source:** WHO, UN Data (2000–2015)  
- **Rows:** ~2,900  
- **Columns:** 22  
- **Key Features:**
  - `Life expectancy`
  - `Adult mortality`
  - `Infant deaths`
  - `GDP`
  - `Schooling`
  - `Income composition of resources`
  - `HIV/AIDS`, `Polio`, `Diphtheria`, `Hepatitis B`
  - `Percentage expenditure`, `Total expenditure`, `BMI`

---

##  Data Preprocessing
Steps performed:
1. Data loading and inspection  
2. Dropping duplicate rows/columns  
3. Handling missing values  
4. Checking data types and consistency  
5. Generating statistical summaries (`describe()`, `info()`)

---

##  Exploratory Data Analysis (EDA)
Major findings:
- **Schooling** and **Income Composition** show the **strongest positive correlation** with life expectancy.  
- **Adult mortality**, **infant deaths**, and **HIV/AIDS** rates have a **strong negative impact**.  
- **Vaccination coverage** (Polio, Diphtheria, Hepatitis B) improves survival, especially among children.  
- **Healthcare expenditure** supports longevity, but **resource allocation** matters more than total spending.  
- **Africa** has the lowest life expectancy; **Europe** and **North America** have the highest.


### Key Insight:
> Economic access and quality of life are far more predictive of life expectancy than public spending alone.

---

##  Visualizations
The project includes visual analyses for:
- Life Expectancy by Continent  
- Correlation Heatmap  
- Relationship between GDP, Schooling, and Life Expectancy  
- Impact of Diseases (HIV/AIDS, Measles, Polio, Diphtheria)  

---

##  Key Insights
- **Socioeconomic conditions** and **education** are the most significant predictors of life expectancy.  
- **High mortality** (adult and infant) and **infectious diseases** drastically reduce lifespan.  
- **Vaccination and healthcare access** improve outcomes.  
- **Economic development alone isn’t enough** — equality in resource access matters most.  
- **Geographical disparities** show that developing countries still face major health challenges.

---

##  Recommendations
1. Invest in **education, income growth, and employment opportunities**.  
2. Expand **vaccination and disease prevention programs**.  
3. Improve **child nutrition and maternal health** to reduce under-five deaths.  
4. Enhance **rural healthcare access** via mobile and digital health solutions.  
5. Promote **healthy lifestyle awareness** (nutrition, exercise, alcohol moderation).  
6. Ensure **universal health coverage** and effective allocation of healthcare spending.  
7. Encourage **international cooperation** to bridge health gaps between regions.  

---

##  Technologies Used
- **Python**   
- **Libraries:** pandas, numpy  
- **Visualization:** Matplotlib & Seaborn  
- **IDE/Tools:** Jupyter Notebook, Power BI (for additional visuals)

---
##  Conclusion
Life expectancy is influenced by **multiple interconnected factors** — education, income, healthcare, and disease control.  
Focusing on **resource access, health equity, and preventive healthcare** can significantly enhance longevity across the world.

---


