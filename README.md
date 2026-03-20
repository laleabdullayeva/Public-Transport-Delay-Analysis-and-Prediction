# 🚌 Public Transport Delay Prediction

## 📌 Project Overview
This project uses Machine Learning to predict delays in public transportation systems such as buses, metro, trains, and trams.  

The main objective is to analyze the key factors that contribute to delays in urban transit and build a predictive model capable of determining whether a scheduled trip will be delayed.  

The final model achieves approximately **75% accuracy**, demonstrating the effectiveness of data-driven approaches in transportation analysis.

## 📊 Dataset Description
The dataset contains over **2,000 records** with **26 features**, covering multiple aspects that influence transport delays.

### Key Feature Groups:
- **Weather Metrics:** temperature, humidity, wind speed, precipitation (mm)  
- **Temporal Factors:** scheduled departure time (hour, minute), weekday, peak hour indicators  
- **Transit Details:** transport type (Bus, Metro, Train, Tram), estimated event attendance  
- **External Factors:** traffic congestion index, holiday status  
## 🛠️ Tech Stack
- **Programming Language:** Python 3.x  
- **Data Analysis:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn (Random Forest, Logistic Regression) 
- **Visualization:** Matplotlib, Seaborn  

## 🚀 Model Performance & Insights
Multiple machine learning models were tested to identify the best-performing approach:

- **Random Forest (Optimized):** 75% Accuracy  
- **Logistic Regression:** 75% Accuracy  

The results show that both Random Forest and Logistic Regression provide strong and stable performance for this classification problem.

## 🎯 Conclusion
This project highlights how machine learning can be applied to real-world transportation problems. By analyzing environmental, temporal, and operational factors, it is possible to make reliable predictions about delays and improve planning strategies.
