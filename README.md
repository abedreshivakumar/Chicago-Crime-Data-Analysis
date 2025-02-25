# Big Data Technologies (CSP-554)

## Team Project: Chicago Crime Analysis (Theme #08)

## Team Members

| **Name**                     | **Hawk ID**   | **Email**                         |
|------------------------------|---------------|-----------------------------------|
| Akshitha Bedre               | A20544641     | abedreshivakumar@hawk.iit.edu     |
| Fnu Anvika                   | A20561884     | aanvika@hawk.iit.edu              |
| Koushik Choudary Bhuma       | A20561884     | kbhuma@hawk.iit.edu               |
| Sudipta Banerjee             | A20460632     | sbanerjee5@hawk.iit.edu           |
| Srujith Borra               | A20562890     | sborra@hawk.iit.edu               |


## Overview

This project analyzes crime data from Chicago to identify trends in criminal activity and predict future crime incidents. We use machine learning models like K-Nearest Neighbors (KNN) and Random Forest to analyze and predict crime locations based on historical data.

## Dataset

The dataset used is the Chicago Police Department's crime data from 2001 to 2021, containing over 6 million reported criminal incidents. It includes information such as:

- **Date and Time**
- **Primary Type of Crime**
- **Location Description**
- **Arrest Status**
- **Geographic Coordinates**
- **Community Area**

## Objectives

- Identify temporal and spatial trends in crime occurrences
- Build predictive models (KNN and Random Forest) to forecast crime occurrences
- Explore relationships between crime type, time of day, and location

## Tools and Libraries Used

- **Python**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **Folium** and **GeoPandas** for geospatial analysis
- **Scikit-learn** for machine learning models

## Data Preprocessing

- Handling missing values using KNN imputation
- Feature engineering (e.g., extracting time-based features)
- Normalizing/scaling features
- Encoding categorical variables

## Exploratory Data Analysis (EDA)

### Temporal Analysis
- Crime trends over years
- Crime distribution by month, day of the week, and hour

### Spatial Analysis
- Crime location density heatmap
- Neighborhood crime distribution
- Crime clusters using KMeans

### Correlation Analysis
- Correlation matrix of numerical variables
- Crime type correlations
- Time and location relationships

## Predictive Modeling

### K-Nearest Neighbors (KNN)
- Used for predicting crime locations
- Achieved **72% accuracy** in predicting crime locations

### Random Forest
- Used for predicting crime types and locations
- Achieved **83% accuracy**, outperforming KNN
- Identified key predictors: hour of day, crime type, and neighborhood

## Results

| Model           | Accuracy |
|------------------|----------|
| KNN              | 72%      |
| Random Forest    | 83%      |

### Key Findings
- Random Forest outperformed KNN in predicting crime locations and types.
- Temporal patterns identified, such as peak crime hours and seasonal trends.
- Geospatial analysis revealed variations in crime density across neighborhoods.
- Environmental correlations noted, with peak crime rates during summer months and evening hours.

## Challenges Faced

- Data quality issues and imbalanced dataset
- Model overfitting
- Computational resource limitations
- Geospatial processing challenges

## Future Work

- Incorporate additional external data (weather, economic indicators)
- Explore deep learning models (CNN, LSTM) for complex pattern recognition
- Develop a real-time crime prediction system
- Optimize models for larger datasets and real-time streams

## Acknowledgments

- Chicago Police Department for providing the crime data
- Professor Joseph Rosen for guidance and feedback
- Illinois Institute of Technology for resources and support

## References

[1] B. Sivanagaleela and S. Rajesh, “Crime analysis and prediction using fuzzy c-means algorithm,” in *2019 3rd International Conference on Trends in Electronics and Informatics (ICOEI)*, 2019, pp. 595–599.

[2] N. V. Chawla, K. W. Bowyer, L. O. Hall, and W. P. Kegelmeyer, “SMOTE: Synthetic minority over-sampling technique,” *Journal of Artificial Intelligence Research*, vol. 16, pp. 321–357, 2002.

[3] Scikit-learn Documentation, “K-nearest neighbors,” 2024. [Online]. Available: [https://scikit-learn.org/stable/modules/neighbors.html](https://scikit-learn.org/stable/modules/neighbors.html)

[4] L. Breiman, “Random forests,” *Machine Learning*, vol. 45, no. 1, pp. 5–32, 2001.

[5] Folium Documentation, “Folium: Python data. leaflet.js maps,” 2024. [Online]. Available: [https://python-visualization.github.io/folium/](https://python-visualization.github.io/folium/)

[6] X. Ma, J. Keung, P. He, Y. Xiao, X. Yu, and Y. Li, “A semisupervised approach for industrial anomaly detection via self-adaptive clustering,” *IEEE Transactions on Industrial Informatics*, vol. 20, no. 2, pp. 1687–1697, 2024.

[7] Nature, “The AI that can beat human players at Dota 2,” *Nature*, November 2020, accessed: 2024-10-19. [Online]. Available: [https://www.nature.com/articles/d41586-020-03348-4](https://www.nature.com/articles/d41586-020-03348-4)

[8] S. Yadav, M. Timbadia, A. Yadav, R. Vishwakarma, and N. Yadav, “Crime pattern detection, analysis & prediction,” in *2017 International Conference of Electronics, Communication and Aerospace Technology (ICECA)*, 2017, pp. 225–230.

[9] R. Yadav and S. K. Sheoran, “Crime prediction using auto regression techniques for time series data,” in *2018 3rd International Conference and Workshops on Recent Advances and Innovations in Engineering (ICRAIE)*, 2018, pp. 1–5.

[10] X. Zhao, H. Yoon, and J. Bae, “Spatio-temporal analysis of crime patterns in urban areas,” *International Journal of Geographical Information Science*, vol. 35, no. 9, pp. 2345–2362, 2021.

