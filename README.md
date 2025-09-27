## 📖 Project Overview  
- **Goal**: Assess launch success, landing outcomes, and best launch sites for cost estimation and competitiveness.  
- **Key Questions**:  
  - How to estimate the total cost for launches?  
  - Where is the best place to launch?  

## 🔬 Methodology  
- **Data Collection**: SpaceX API + Wikipedia Web Scraping  
- **Data Wrangling**: Cleaning & labeling landing outcomes  
- **Exploratory Data Analysis (EDA)**: Visualization & SQL queries  
- **Interactive Analytics**: Folium Maps + Plotly Dash dashboards  
- **Machine Learning**: Logistic Regression, SVM, Decision Tree, KNN  

## 📊 Key Results  
- **Launch Insights**  
  - 4 main launch sites (coastal, safe, with strong logistics)  
  - KSC LC-39A & CCAF SLC-40 are the top-performing sites  
  - Launch success rates improved after 2013  

- **Payload & Orbit**  
  - Payloads > 9,000kg had excellent success rates  
  - GEO, ES-L1, HEO, and SSO orbits showed the best performance  

- **Machine Learning**  
  - Decision Tree Classifier was the most accurate model (87%+ accuracy, 94% on test data)  
  - Predictive analysis can forecast landing success and inform cost efficiency  


## ✅ Conclusions  
- SpaceY can strategically compete by:  
  - Focusing on **KSC LC-39A** for launches  
  - Prioritizing **heavier payloads**  
- Decision Tree models can reliably predict landing success.  
- Success rates will likely keep improving with technology refinement.  


## ⚡ Challenges  
- Reproducibility requires setting `np.random.seed`  

This project combines **data collection, visualization, and machine learning** to deliver insights into commercial space launch competitiveness.  
