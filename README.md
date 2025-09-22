This project focuses on predicting the State of Health (SOH) and Remaining Useful Life (RUL) of lithium-ion batteries, which is critical for ensuring safety, reliability, and performance in electric vehicles and energy storage systems.

A hybrid CNN–LSTM deep learning model was developed using NASA’s Li-ion battery dataset. The CNN layers extract spatial features from voltage, current, and capacity cycles, while the LSTM layers capture temporal dependencies, enabling accurate sequence-based predictions of battery degradation patterns.

To bridge the gap between offline model training and real-world deployment, a Digital Twin was designed in MATLAB/Simulink. The Digital Twin replicates the physical behavior of lithium-ion batteries in real time and integrates the trained CNN–LSTM model to provide continuous monitoring, anomaly detection, and predictive maintenance insights.

Key contributions include:

Data preprocessing and feature engineering from NASA’s battery datasets.

Implementation of a hybrid CNN–LSTM architecture for SOH and RUL prediction.

Comparison of model accuracy against standalone CNN, RNN, and LSTM approaches.

Development of a Digital Twin framework in MATLAB/Simulink for simulation and real-time integration with external sensor data.

This project demonstrates how combining AI-driven modeling with Digital Twin technology can enhance the reliability of electric vehicle batteries and enable smarter predictive maintenance strategies.
