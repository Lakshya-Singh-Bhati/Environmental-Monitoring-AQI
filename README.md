# Environmental-Monitoring-AQI
AI-based Air Quality Index (AQI) Prediction System – Edunet Foundation Internship (4 Weeks)

WEEK 1:
📌 Internship Information
- **Organization:** Edunet Foundation  
- **Internship Theme:** Environmental Monitoring & Pollution Control  
- **Duration:** 4 Weeks Virtual Internship  
- **Week 1 Submission:** 30% Project Progress  

📌 Project Title  
**AI-based Air Quality Index (AQI) Prediction System**

📌 Problem Statement  
Air pollution is one of the biggest environmental challenges faced globally.  
Increasing industrialization, traffic emissions, and urbanization have led to poor air quality, which directly impacts human health and the environment.  

There is a strong need for intelligent systems that can **predict air quality levels in advance** to help governments, organizations, and individuals take preventive measures.  

📌 Objectives  
1. Collect real-world **Air Quality data** (PM2.5, PM10, NO₂, CO, O₃, SO₂, temperature, humidity, wind speed).  
2. Preprocess and analyze the dataset to identify key factors affecting AQI.  
3. Develop **Machine Learning models** to predict AQI levels based on historical and environmental data.  
4. Compare multiple models (Linear Regression, Decision Tree, Random Forest, XGBoost).  
5. Provide **visual insights** (graphs & charts) to show pollution trends.  
6. Create a simple system that can help in **forecasting AQI** for proactive environmental monitoring.  

📌 Dataset Information  
- **Source:**  
  - [Kaggle AQI Dataset](https://www.kaggle.com/)  
  - [CPCB (Central Pollution Control Board, India)](https://cpcb.nic.in/)  
- **Features:** PM2.5, PM10, NO₂, SO₂, CO, O₃, temperature, humidity, wind speed.  
- **Target Variable:** AQI (Air Quality Index).  
- **Format:** CSV / time-series data.  

📌 Expected Outcomes  
- A trained ML model capable of **predicting AQI levels** with good accuracy.  
- Insights on **which pollutants contribute most** to poor air quality.  
- Visual dashboard showing **pollution trends and predictions**.  
- Contribution towards **environmental monitoring & pollution control**.  

📌 Work Completed (Till Week 1 – 30%)  
- ✅ Finalized **project theme**: Environmental Monitoring & Pollution Control  
- ✅ Chosen **problem statement**: Air Quality Prediction  
- ✅ Identified **datasets** from Kaggle & CPCB  
- ✅ Outlined **objectives, methods, and expected outcomes**  


WEEK 2:

📌 Work Completed (60% Project Progress)

📌 Data Preprocessing & Cleaning

Checked dataset for missing values and duplicates

Handled missing values to ensure data quality

Encoded categorical features (Country, Status) using Label Encoding

📌 Exploratory Data Analysis (EDA)

Plotted AQI value distributions

Visualized correlations between pollutants (PM2.5, PM10, NO₂, etc.) and AQI

Counted AQI status categories (Good, Moderate, Poor, etc.)

Compared AQI values across different countries

📌 Model Building (Baseline Linear Regression)

Performed train-test split (80:20)

Trained Linear Regression model on training data

Evaluated model performance:

Mean Squared Error (MSE): 900.20

R² Score: 0.61

📌 Insights

Baseline model explains ~61% of AQI variance

PM2.5, PM10, and NO₂ are the strongest contributors to AQI

Linear Regression provides a solid starting point for further improvements
