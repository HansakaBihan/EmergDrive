# EmergDrive
Research group R25-021

Group members : 
S.A.T.R Satharasinghe - IT21806568
H.P.H Bihan - IT21298776
S.M.R.K Suwendra - IT21801822
R.A.W.Y Ranatunge - IT21290510

Project Scope  - This research proposes an AI-powered system to reduce emergency vehicle delays in urban traffic by integrating real-time vehicle detection (YOLO), siren recognition (using audio processing and CNN), and adaptive traffic signal control via reinforcement learning. It also includes an HCI-driven mobile app for emergency drivers to enhance communication with traffic systems, aiming for a scalable, cost-effective, and responsive solution. 

Component 1 ( IT21806568 ) : Develop a real time traffic detection system using object detection

SCOPE : This research aims to detect traffic congestion using object detection techniques. The objective is to compare the accuracy of YOLO with other object detection models, including Faster R-CNN, Mask R-CNN, and R-CNN, to identify the most effective method for detecting vehicles in traffic. A custom object detection model will also be developed to improve YOLO’s performance. The output will provide real-time analysis of vehicle count and congestion levels using CCTV footage.

Technologies Used:
Object Detection: YOLO, Faster R-CNN, Mask R-CNN, R-CNN

Custom Model: Improving YOLO performance

Video Processing: OpenCV, TensorFlow

Real-time Analysis: CCTV Footage Processing

Framework: TensorFlow Object Detection API, Python

Component 2 ( IT21298776 ): Develop a real time, cost effective siren detection system

SCOPE : The study aims to develop a cost-effective system that prioritizes emergency vehicles by detecting sirens and adjusting traffic signals in real time. It uses audio processing (MFCC), machine learning (CNNs), and predictive algorithms to improve detection accuracy in noisy environments and reduce emergency response times. The system is designed to be scalable, adaptable, and cost-efficient, offering a better solution than existing systems.

Component 3 ( IT21290510 )  : HCI-Driven Real-Time Accident Severity Prediction System

SCOPE : This module focuses on predicting the severity of traffic accidents in real time, specifically designed to support emergency response systems. By leveraging a Human-Computer Interaction (HCI) approach, the system delivers intuitive alerts and adaptive UI changes based on predicted risk levels (High or Low), helping emergency drivers make informed decisions during critical situations.

Key Technologies Used:
	•	Python – Primary language for data preprocessing and model development.
	•	TensorFlow / Keras – For building and training deep learning models.
	•	Pandas & NumPy – Efficient handling and transformation of datasets.
	•	Scikit-learn – Preprocessing tools and evaluation metrics.
	•	Matplotlib – Visualizing data distribution and model performance.
	•	Joblib – Model serialization for deployment.
	•	Kaggle Notebooks (GPU P100) – Used for training the model on cloud-based infrastructure.

Key Features:
	•	Deep learning-based accident severity prediction (High / Low risk).
	•	Integration with real-time APIs for weather, geolocation, and infrastructure data.
	•	Adaptive user interface that changes based on severity predictions.
	•	Voice alert integration for real-time driver notification.
	•	Designed for emergency scenarios with usability under stress in mind.

Component 4 ( IT21801822 )  : Emergency Vehicle Routing Using Predictive Traffic Delay and Dynamic Path Optimization

SCOPE: This project focuses on optimizing emergency vehicle routing by comparing conventional real-time routes (e.g., Google Maps) with an intelligent alternative route that incorporates dynamic traffic light control and machine learning-based delay prediction. The system aims to minimize total response time by prioritizing paths with fewer predicted delays, giving emergency services a faster and smarter routing strategy.
______________________________________
Key Technologies Used:
•⁠  ⁠Python – Core language for data handling, pathfinding, and model logic.
•⁠  ⁠scikit-learn – For training delay prediction models using real-world traffic datasets.
•⁠  ⁠Pandas & NumPy – Efficient feature extraction and data preprocessing.
•⁠  ⁠Joblib – Model serialization for runtime prediction integration.
•⁠  ⁠Matplotlib & NetworkX – Visualization of route comparisons and network graphs.
•⁠  ⁠OSMNX & OpenStreetMap – For real-world road network modeling and shortest path calculations.
______________________________________
Key Features:
•⁠  ⁠A* Pathfinding Algorithm that adapts dynamically to traffic light delays.
•⁠  ⁠Machine Learning Delay Predictor trained on historical traffic data (hour, day, rain).
•⁠  ⁠Comparison Engine to evaluate baseline (Google Maps) vs smart delay-aware routes.
•⁠  ⁠Route Visualization Module with comparison between distance-only and delay-optimized paths.
•⁠  ⁠Time & Delay Evaluation Engine that estimates total travel time based on distance, predicted congestion, and assumed vehicle speed.
•⁠  ⁠Future Integration Ready for real-time sensor or traffic API inputs to override predictions with live data.
______________________________________
This system is specifically designed to support emergency response teams by avoiding traffic bottlenecks and intelligently rerouting through dynamically prioritized junctions. By combining open geographic data with predictive modeling and algorithmic routing, it delivers a scalable, real-world applicable solution for urban emergency traffic systems.
