🚀 AI-Based Predictive Maintenance System

A Machine Learning project designed to predict industrial equipment failures before they occur. This system enables proactive maintenance, reduces unexpected downtime, optimizes repair scheduling, and extends the lifecycle of critical machinery.


---

📌 Project Overview

Predictive Maintenance is a key component of Industry 4.0 and smart manufacturing. This project uses machine learning and deep learning models to analyze sensor data and classify potential failure types in industrial machines such as pumps, motors, and compressors.

By identifying early warning signs, industries can significantly reduce operational costs and improve equipment efficiency.


---

🎯 Key Objectives

Predict machine failures before breakdown

Compare multiple ML and DL models

Analyze sensor data patterns

Improve maintenance planning through data-driven insights



---

📊 Dataset Description

This project uses a synthetic dataset simulating real-world industrial sensor readings.

🔹 Features Used

Variable	Description

Temperature	Operating temperature (°C)
Vibration	Vibration level (0–1 scale)
Pressure	Internal pressure (bars)
Humidity	Ambient humidity (%)
RPM	Rotations per minute
Voltage	Supply voltage (V)
Current	Current usage (A)
Sound_Level	Noise level (dB)
Oil_Quality	Oil degradation index (0–1)
Load	Machine load percentage (%)
Machine Type	Pump / Motor / Compressor
Component Type	Specific monitored component
Failure Type	Target variable (Mechanical, Electrical, etc.)



---

🧠 Methodology

1️⃣ Data Preprocessing

Synthetic data generation

Data cleaning and encoding

Feature scaling

Train-test split


2️⃣ Model Development

Random Forest Classifier

Decision Tree

Bagging Classifier

LSTM Neural Network (for sequential data analysis)


3️⃣ Model Evaluation

Performance evaluated using:

Accuracy

Precision

Recall

F1 Score



---

📈 Results

Random Forest achieved strong classification accuracy.

LSTM effectively captured temporal dependencies in sensor readings.

Bagging improved model robustness.

Early failure detection helps minimize downtime and improve operational efficiency.



---

🛠 Tech Stack

Python

NumPy

Pandas

Scikit-learn

TensorFlow / Keras

Matplotlib

Seaborn

Jupyter Notebook



---

▶️ How to Run the Project

1. Clone the repository:

git clone https://github.com/your-username/ai-predictive-maintenance-system.git


2. Navigate into the project folder:

cd ai-predictive-maintenance-system


3. Install required libraries:

pip install pandas numpy scikit-learn tensorflow matplotlib seaborn


4. Open the Jupyter Notebook:

jupyter notebook


5. Run all cells in Predictive_Maintenance_Using_Machine_Learning.ipynb




---

💡 Future Improvements

Add real-time dashboard using Streamlit

Deploy model using Flask or FastAPI

Implement Explainable AI (SHAP)

Integrate real industrial IoT datasets



---

📌 Business Impact

This project demonstrates how AI can reduce equipment downtime, improve maintenance scheduling, and optimize manufacturing efficiency — aligning with modern smart factory solutions.


---

👩‍💻 Author

Keerthi
B.Tech – Artificial Intelligence & Machine Learning
