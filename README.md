
**Title**: AI-IoT Driven Real-Time Air Pollution Monitoring
and Mapping for Sustainable Urban Planning.<br>
**Abstract**: Air pollution poses a critical threat to public health,
environmental quality, and urban sustainability, driven by rapid
urbanization, industrial activity, vehicular emissions, and inefficient
waste management. Tackling this challenge demands robust mon-
itoring, predictive modeling, pollution mapping, and effective man-
agement strategies. This study presents an AI-IoT Driven Real-Time
Air Pollution Monitoring and Mapping System for sustainable urban
planning, integrating IoT technology and machine learning for real-
time monitoring of key air quality parameters, including PM2.5, CO,
NO2, SO2, O3, and compute the Air Quality Index (AQI), a standardized scale ranging from Good (0–50) to Hazardous
(301–500). We evaluate multiple machine learning algorithms, namely Random Forest, XGBoost, CatBoost, Gradient
Boosting, and SVM, alongside a proposed stacked ensemble model, to to support air pollution monitoring, predict pollution
trends, identify high-risk areas, and generate actionable mitigation insights. The stacked ensemble achieves the highest
performance with 98.73% (±0.21%) cross-validation accuracy. The system further delivers real-time alerts to residents and
authorities, enabling avoidance of polluted zones and timely interventions. In addition, adaptive route optimization and
IoT-enabled waste monitoring ensure timely waste collection, reducing emissions from unmanaged waste and supporting
urban planning. Together, these capabilities form an integrated, data-driven framework for improving urban air quality and
enabling evidence-based smart city planning.
![image alt](https://github.com/UA-CVML/AI-IoT-Driven-Real-Time-Air-Pollution-Monitoring-and-Mapping-for-Sustainable-Urban-Planning/blob/main/abstract%20(1).png)


**Project Overview:**

Air pollution has become a major challenge affecting human health, environmental sustainability, and urban development. Rapid urbanization, industrial emissions, transportation, and poor waste management significantly contribute to deteriorating air quality. This project proposes an AI-IoT driven real-time air pollution monitoring and mapping system designed to support sustainable urban planning through data-driven decision making.

**Project Objectives:**

The main objectives of this project are:

• A stacked ensemble learning approach that improves the
accuracy and robustness of air quality predictions.<br>
• Integration of IoT sensors and machine learning to
monitor and predict real-time air pollution levels across
standard health categories (Good, Hazardous, Moderate,
Unhealthy, etc.).<br>
• A dynamic pollution mapping interface with color-coded
visuals and mobile/web alerts when pollution exceeds
safe thresholds.<br>
• A unified cloud platform for data collection, analysis,
visualization, and decision support to enhance urban air
quality sustainability.<br>

**System Architecture:**

The proposed system consists of four main layers:
![image alt](https://github.com/UA-CVML/AI-IoT-Driven-Real-Time-Air-Pollution-Monitoring-and-Mapping-for-Sustainable-Urban-Planning/blob/main/architec%20(1).png)

**Data Collection Layer**:
IoT sensors continuously collect environmental data including particulate matter and gas concentrations.

**Data Transmission Layer:**
Sensor data is transmitted to a cloud platform using wireless communication protocols.

**Data Processing Layer:**
Machine learning algorithms process the collected data for prediction and analysis.

**Application Layer:**
A mobile and web interface provides visualization, AQI status, alerts,route recommendations, waste management panel.

**Methodology**

**Data Acquisition:** Environmental data is collected from IoT sensor nodes and public air quality datasets.

**Data Preprocessing:** Data cleaning, normalization, and feature engineering are performed to improve model performance.

**Machine Learning Models:**
The study evaluates several supervised learning algorithms:
 Random Forest, XGBoost, CatBoost, Gradient Boosting, Support Vector Machine (SVM)

A stacked ensemble model is proposed to combine the strengths of individual models.
![image alt](https://github.com/UA-CVML/AI-IoT-Driven-Real-Time-Air-Pollution-Monitoring-and-Mapping-for-Sustainable-Urban-Planning/blob/main/Stack.jpg)

**Model Evaluation**
![image alt](https://github.com/UA-CVML/AI-IoT-Driven-Real-Time-Air-Pollution-Monitoring-and-Mapping-for-Sustainable-Urban-Planning/blob/main/result.png)
Left figure compares Accuracy, Precision, Recall, and F1-Score for multiclass AQI prediction across all models. All achieved values above 0.97, indicating reliable performance.Among base learners, Gradient Boosting showed the best bal-
ance (0.986 across all metrics), followed closely by XGBoost and CatBoost, while Random Forest remained competitive. The proposed stacked ensemble outperformed all models, achieving the highest scores (Accuracy 0.988, Precision 0.989, Recall 0.988, F1 0.988). This balanced improvement highlights effective bias–variance reduction and confirms the suitability of stacked ensembles for stable, practical air quality monitor-ing.<br>
Right figure compares multiclass and binary AQI prediction accuracies of all models. Blue bars show multiclass accuracy
across six AQI categories, while orange bars represent bi-nary Safe–Harmful accuracy. Among base learners, Gradient
Boosting achieved the highest multiclass accuracy (98.62%), followed by XGBoost (98.33%), CatBoost (98.18%), and
Random Forest (97.71%). The proposed stacked ensemble outperformed all models, reaching 98.83% multiclass and 99.85% binary accuracy. All models performed better in binary tasks, indicating lower complexity in Safe–Harmful classifica-tion. High binary accuracies (99.42%–99.85%) confirm strong detection of harmful conditions. The ensemble’s superior performance demonstrates robust generalization by effectively capturing nonlinear pollutant interactions and temporal air quality variations.

**Key Features of the System**

**Real-Time Monitoring:**
Continuous monitoring of major air pollutants using IoT sensors.

**Pollution Prediction:**
ML models forecast pollution trends to support proactive planning.

**Pollution Mapping:**
Geospatial visualization identifies highly polluted areas and recommend safer routes .

**AQI Calculation:**
The system calculates AQI values ranging from Good (0–50) to Hazardous (301–500).

**Smart Alerts:**
Automatic notifications are sent to citizens and authorities when pollution exceeds safe limits.

**Route Optimization:**
The system suggests safer alternative routes based on pollution levels.

**Waste Monitoring Integration:**
IoT-based waste monitoring supports timely waste collection, reducing pollution from unmanaged waste.

**Expected Outcomes**

**The proposed system is expected to:**

Improve urban air quality monitoring efficiency
Provide accurate pollution prediction
Enable data-driven environmental policies
Reduce exposure to harmful pollution
Support smart and sustainable city development

**Conclusion**

This study proposes a AI-Driven Pollution Prediction and Mapping System for Sustainable Urban Planning that inte-grates IoT sensing with machine learning to address urban air pollution. Distributed sensors continuously measure P M2.5,CO, N O2, SO2, O3, humidity, and wind parameters, trans-mitting data via Wi-Fi, LoRa, or cellular networks for real-time analysis, pollution mapping, and user alerts. The system also incorporates IoT-based waste monitoring to optimize col- lection routes and reduce emissions. For prediction, XGBoost, CatBoost, Gradient Boosting, SVM, and a stacked ensemble were evaluated. The proposed ensemble, combining boosting best performance (98.83% accuracy, 98.9% precision, 98.8% recall, 98.8% F1-score). Its novelty lies in unifying sensing, analytics, mapping, and adaptive waste management. While results are strong, further work is needed on sensor calibration, generalization, privacy, and large-scale deployment.



