# Anomalous-Ship's Engine Functionality Detection with Statistical and Machine Learning Techniques
# Background Context
Reliable engine performance is essential to the maritime industry, where unplanned downtime can disrupt logistics, increase operational costs, and pose safety risks. This project focuses on detecting anomalous behavior in ship engine performance using sensor data. The dataset includes six key features—such as engine RPM, lubrication oil pressure, and fuel pressure—that provide valuable insights into engine conditions. Although anomalies represent only about 1% to 5% of the data, early detection is critical for preventing mechanical failures, reducing maintenance costs, and ensuring uninterrupted vessel operation.
# Objective
The objective of this project is to develop a robust and reproducible anomaly detection system that can identify potential issues in ship engine performance using sensor data. The system leverages both statistical and machine learning techniques to detect abnormal patterns across six key engine features. Specifically, the project aims to:
  - Select and implement suitable methods for anomaly detection, including univariate and multivariate approaches.
  - Define appropriate thresholds for identifying abnormal observations.
  - Compare the effectiveness of each method in capturing anomalies.
# Key Outcomes
This project showcases the application of statistical and machine learning methods to detect anomalies in ship engine performance. By developing and comparing multiple detection techniques, the project demonstrates a structured approach to data-driven problem solving in an operational context.

The following methods were implemented:
 - **Interquartile Range (IQR) Method**: A straightforward, interpretable statistical technique used to detect outliers in individual features.
 - **One-Class SVM**: A multivariate anomaly detection method capable of modeling complex boundaries between normal and abnormal engine behavior, albeit sensitive to parameter tuning and computational cost.
 - **Isolation Forest**: An efficient, scalable algorithm that isolates anomalies by randomly partitioning the feature space, well-suited for high-dimensional datasets.
# Showcased Skills

  - **Exploratory Data Analysis & Feature Engineering**: Analyzed sensor data distributions, visualized trends, and prepared key engine features for anomaly detection.

  - **Statistical & Machine Learning Methods**: Applied the Interquartile Range (IQR), One-Class SVM, and Isolation Forest techniques to detect outliers and abnormal patterns.

  - **Model Evaluation & Comparison**: Assessed the strengths and limitations of each method, balancing interpretability, scalability, and detection accuracy.

  - **Clean, Reproducible Coding**: Developed well-structured and documented Python code using pandas, scikit-learn, and matplotlib, ensuring the analysis is transparent and reusable.
