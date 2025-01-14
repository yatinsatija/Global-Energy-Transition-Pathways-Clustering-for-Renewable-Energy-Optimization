# Global Energy Transition Pathways

This project explores the global transition from fossil fuels to renewable energy, aiming to identify tailored pathways for countries at various stages of energy transition. Through clustering, predictive modeling, and data analysis, we provide actionable insights into renewable adoption strategies.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Methodology](#methodology)
4. [Data Sources](#data-sources)
5. [Setup Instructions](#setup-instructions)
6. [Results](#results)
7. [Future Enhancements](#future-enhancements)

---

## **Introduction**
The global need for sustainable energy has never been more critical. This project analyzes historical energy consumption, renewable adoption rates, and nuclear energy contributions across countries. By leveraging clustering and predictive techniques, we provide insights into optimal energy transition strategies.

---

## **Objectives**
1. Segment countries into distinct energy consumption profiles.
2. Identify factors influencing renewable and nuclear energy adoption.
3. Develop predictive models to inform energy policy decisions.

---

## **Methodology**
### **Workflow**
1. **Data Loading and Preprocessing**:
   - Combined multiple datasets on energy consumption, renewable adoption, and nuclear energy.
   - Engineered features like total energy consumption and proportional energy shares.

2. **Scaling and Dimensionality Reduction**:
   - Normalized numerical features using `StandardScaler`.
   - Applied Principal Component Analysis (PCA) for visualization.

3. **Clustering**:
   - Used KMeans and DBSCAN for country segmentation.
   - Validated clusters with Elbow and Silhouette methods.

4. **Predictive Modeling**:
   - Built linear regression models to analyze factors influencing energy consumption.

---

## **Data Sources**
1. **[World Energy Consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption):** Provides global energy metrics.
2. **[Energy Consumption Prediction](https://www.kaggle.com/datasets/mrsimple07/energy-consumption-prediction):** Captures environmental and operational energy consumption factors.
3. **[Nuclear Energy Dataset](https://www.kaggle.com/datasets/alistairking/nuclear-energy-datasets):** Details nuclear energy trends and infrastructure.

---

## **Setup Instructions**
1. Clone this repository:
   ```bash
   git clone https://github.com/yatinsatija/Energy-Demand-Forecasting-and-Optimization-with-Machine-Learning.git
