# Machine-failure-detection-analysis-report-ML-DA-
Predictive Maintenance using Data Analytics &amp; Machine Learning


📘 Overview

In today’s industrial era, unplanned machine downtime causes significant losses in productivity, repair costs, and reliability. This project, Machine Failure Detection and Analysis, applies data analytics and machine learning to predict machine failures before they occur.

By leveraging sensor data such as temperature, pressure, vibration, and current, the system identifies early warning signs of malfunction, enabling industries to shift from reactive to predictive maintenance — reducing downtime and maintenance costs while improving equipment longevity.

🚀 Features

✅ Data Preprocessing & Cleaning – Removes duplicates, handles missing data, and normalizes features.
✅ Feature Engineering – Extracts important indicators using statistical and correlation analysis.
✅ Model Training & Evaluation – Uses ML algorithms like Random Forest, Isolation Forest, and Gradient Boosting.
✅ Performance Visualization – Displays confusion matrix, ROC curve, feature importance, and sensor correlations.
✅ Tkinter Dashboard Interface – Interactive desktop UI for real-time visualization and metric exploration.
✅ PDF Report Generation – Summarizes the analysis, results, and recommendations in a downloadable format.

🧩 System Architecture
Sensor Data → Data Preprocessing → Feature Engineering 
     ↓
Model Training → Prediction → Visualization Dashboard → Report Generation


The architecture integrates data collection, preprocessing, model analytics, and decision support into a single framework.

🧠 Technologies Used
Category	Tools & Libraries
Programming Language	Python 3.9+
Data Processing	Pandas, NumPy
Machine Learning	Scikit-learn
Visualization	Matplotlib, Seaborn
Interface	Tkinter
Reporting	ReportLab
📊 Dashboard Preview

An interactive Tkinter-based Analysis Dashboard provides:

Confusion Matrix

Feature Importance Chart

ROC Curve

Correlation Heatmap

Failure Distribution Plot

Temperature vs Pressure Relationship

Each graph opens dynamically for better interpretation and visual analytics.

🧪 Dataset

The dataset includes machine operational and sensor readings over time, typically with the following attributes:

Feature	Description
Temperature	Machine operating temperature
Pressure	Input/Output pressure
Vibration	Mechanical vibration intensity
Current Sensor (CS)	Electrical current usage
Air Quality (AQ)	Surrounding air index
VOC	Volatile Organic Compound level
Rotational Speed (RP)	RPM of machine components
Input Pressure (IP)	Feed pressure value
Fail	Binary indicator (1 = Failure, 0 = Normal)

Dataset Source: Kaggle Predictive Maintenance Dataset (2024)

⚙️ How to Run
1️⃣ Clone Repository
git clone https://github.com/Adhityan15/Machine-Failure-Detection.git
cd Machine-Failure-Detection

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Jupyter Notebook (Training & EDA)
jupyter notebook Machine_failure_detection.ipynb

4️⃣ Launch the Tkinter Dashboard
python analysis_dashboard.py

🧩 Model Evaluation
Metric	Description
Accuracy	Overall correctness of predictions
Precision	True failures detected out of all predicted failures
Recall	Proportion of actual failures correctly identified
F1 Score	Harmonic mean of precision and recall
ROC-AUC	Model’s capability to distinguish between failure and normal states

Visuals include:

Confusion Matrix

F1-score bar chart

ROC Curve

Feature Importance

💻 Sample Output
Machine ID: MCH_103
Condition Status: Failure Risk
Recommendation: Inspect coolant system and vibration dampers.
Generated Report: MCH_103_maintenance_report.pdf

🏁 Results & Insights

Achieved ~94% accuracy on test data.

Temperature, Pressure, and Vibration emerged as key predictive indicators.

Early detection allowed potential downtime reduction by 35–40% in simulation.

🔮 Future Enhancements

Integration with IoT devices for real-time streaming data.

LSTM/CNN deep learning models for sequential time-series analysis.

Explainable AI (SHAP/LIME) integration for transparent predictions.

Automated maintenance scheduling based on predicted failure probability.

🧑‍💻 Developer

R. Adhityan
🎓 B.Tech Artificial Intelligence & Data Science
📍 Panimalar Engineering College, Chennai
📬 GitHub: Adhityan15

📚 References

Lee, J. et al. (2015). A Cyber-Physical Systems Architecture for Industry 4.0.

Wang, T. et al. (2019). Machine Learning for Predictive Maintenance: A Review.

Breiman, L. (2001). Random Forests.

Kaggle Predictive Maintenance Dataset (2024).

Bousdekis, A. et al. (2017). Predictive Maintenance 4.0.

⭐ If you found this project helpful, give it a star on GitHub and share your feedback!
