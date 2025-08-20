# **🔥Fire Weather Index Prediction**

A machine learning-powered web application that predicts the Fire Weather Index (FWI) using various environmental parameters such as temperature, humidity, wind speed, and more. This project leverages the Algerian Forest Fires Dataset and applies regression models to provide accurate predictions.

**📌 Features**

🌡 Predicts Fire Weather Index based on user inputs.
📊 Uses Ridge Regression for model predictions.
📈 Preprocessing with Scaler for normalized inputs.
🌐 Flask web interface with a glassmorphism design and background video.
📁 Organized project structure for easy understanding and maintenance.

**📂 Project Structure**
.
1. ├── Dataset

       └── Forest_updated.csv             # Dataset used for training

2. ├── Jupyter Notebook

       └── End to End Algerian Forest Fires Dataset...ipynb # Data preprocessing, training & evaluation

3. ├── models

       ├── ridge.pkl                       # Trained Ridge Regression model
       └── scaler.pkl                      # Scaler for input normalization

4. ├── templates

       ├── home.html                       # Web UI template
       └── index.html                      # Alternate HTML template

5. ├── application.py                      # Flask application


6. ├── README.md                           # Project documentation


**🚀 How It Works**

Data Preprocessing – The dataset is cleaned and scaled.
Model Training – Ridge Regression is trained to predict the FWI.
Web Application – A Flask app collects user inputs, processes them, and displays predictions.

**🛠 Installation & Setup**

1️⃣ Clone the Repository
git clone https://github.com/AshutoshKumar18/fire-weather-index-prediction.git
cd fire-weather-index-prediction

2️⃣ Create a Virtual Environment & Activate
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python application.py

5️⃣ Open in Browser
http://127.0.0.1:5000

**🧪 Example Input & Output
Input:**

Temperature: 25.5°C
Relative Humidity: 60.2%
Wind Speed: 15.3 km/h
Rainfall: 2.1 mm
Fine Fuel Moisture Code: 85.4
Duff Moisture Code: 45.2
Initial Spread Index: 8.5
Fire Danger Class: 3
Region Code: 1

**Output:**

🔥 Fire Weather Index Prediction: 12.4


**📚 Technologies Used**

Python 🐍
Flask 🌐
Pandas, NumPy, Scikit-learn 📊
HTML, CSS 🎨
Jupyter Notebook 📓

**🤝 Contributing**

Contributions, issues, and feature requests are welcome!

Feel free to use this repository and submit a pull request.

