
# Power System Fault Detection and Classification using Machine Learning:

This system is designed to automatically classify power faults in real-time using a supervised machine learning model. It enables early detection, quicker response times, and improved reliability in power grid management.


## About
This system is designed to automatically classify in real - time using
## Dataset
The dataset includes:
- Fault ID (Unique Identifier)
- Fault Type (Target label)
- Voltage, Current, Power Load
- Weather: Temperature, Wind Speed, Weather Condition
- Maintenance Status, Component Health
- Fault Location (Latitude, Longitude)
- Duration of Fault and Downtime

Data can be real-time from sensors or simulated using MATLAB/Simulink.
## Technologies
**Python 3.8+**
- **NumPy, Pandas** – Data processing
- **Scikit-learn** – Machine Learning algorithms
- **Matplotlib, Seaborn** – Data visualization
- **Jupyter Notebook** – Development environment

Optional:
- **TensorFlow/PyTorch** – For deep learning extensions
- **Flask/FastAPI** – For API deployment
## Features

- Automated Fault Detection
Detects abnormal conditions in the power grid in real time using voltage and current data.

- Fault Type Classification
Accurately classifies fault types such as Line-to-Ground, Line-to-Line, Transformer Failure, and Overheating.

- Multi-Source Data Support
Uses electrical, environmental, and maintenance data (e.g., voltage, current, temperature, wind speed, component health).

- Geographic Fault Localization
Includes GPS coordinates to locate faults precisely using latitude and longitude data.

- Intelligent Prediction Engine
Machine learning models like Random Forest provide high accuracy and robustness.

- Interactive Visualization
Visual outputs include confusion matrix, feature importance graphs, and performance plots.

- Customizable & Scalable
Can be extended to include new fault types, more data sources, and real-time deployment via APIs or edge devices.

- Offline & Real-Time Capable
Supports both historical batch predictions and integration with real-time sensor streams.










## Model Workflow

- Data Preprocessing – Clean and normalize input features

- Feature Engineering – Extract electrical and environmental indicators

- Model Training – Train classifier (e.g., Random Forest) on labeled fault data

- Evaluation – Test performance using accuracy, F1-score, confusion matrix

- Deployment – Export trained model for API or real-time monitoring use


## Future Scope
- Integration with SCADA/Smart Grid systems
- Edge deployment using embedded AI devices
- Use of deep learning for sequence-based fault prediction
- Expansion to renewable power sources and microgrids
- Semi-supervised models for unlabeled data