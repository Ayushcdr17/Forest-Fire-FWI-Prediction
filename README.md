🔥 Forest Fire Weather Index (FWI) Prediction

A Machine Learning powered web application that predicts the Fire Weather Index (FWI) using environmental and meteorological parameters from the Algerian Forest Fires Dataset.

Built using Flask + Scikit-learn + Ridge Regression.

🌍 Live Web App Preview

📊 Algerian Forest Fires Dataset
📌 Data Set Information

The dataset contains 244 instances collected from two regions of Algeria:

📍 Bejaia Region (Northeast Algeria)

📍 Sidi Bel-abbes Region (Northwest Algeria)

Each region contains:

122 instances per region

Total: 244 observations

🗓 Time Period

June 2012 – September 2012

📈 Dataset Characteristics

11 Input Attributes

1 Output Attribute (Class)

Classified into:

🔥 Fire (138 instances)

🌿 Not Fire (106 instances)

🧾 Attribute Information
📅 Date Information

Date (DD/MM/YYYY)

Month: June to September

Year: 2012

🌤 Weather Observations

Temp

Temperature at noon (°C)

Range: 22 – 42

RH

Relative Humidity (%)

Range: 21 – 90

Ws

Wind Speed (km/h)

Range: 6 – 29

Rain

Total daily rainfall (mm)

Range: 0 – 16.8

🔥 FWI System Components

FFMC (Fine Fuel Moisture Code)

Range: 28.6 – 92.5

DMC (Duff Moisture Code)

Range: 1.1 – 65.9

DC (Drought Code)

Range: 7 – 220.4

ISI (Initial Spread Index)

Range: 0 – 18.5

BUI (Buildup Index)

Range: 1.1 – 68

FWI (Fire Weather Index)

Range: 0 – 31.1

🎯 Target Variable

Classes

Fire

Not Fire

🧠 Machine Learning Model
🔹 Model Used

Ridge Regression

🔹 Preprocessing

Feature Scaling using StandardScaler

Numerical encoding for categorical features

🔹 Why Ridge Regression?

Handles multicollinearity

Reduces overfitting using L2 regularization

Suitable for continuous target prediction

🏗 Project Architecture
Forest-Fire-FWI-Prediction/
│
├── application.py        # Flask application
├── models/               # Trained ML model & scaler
├── templates/            # HTML files
├── notebooks/            # EDA & Model Training
├── requirements.txt      # Dependencies
└── README.md

🚀 How To Run Locally
1️⃣ Clone Repository
git clone https://github.com/Ayushcdr17/Forest-Fire-FWI-Prediction.git
cd Forest-Fire-FWI-Prediction

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Flask App
python application.py


Open browser:

http://127.0.0.1:5000

💻 Web Application Features

✅ Clean Modern UI
✅ Dropdown selection for Class & Region
✅ Feature scaling before prediction
✅ Real-time FWI prediction
✅ Organized project structure

📌 Future Improvements

Deploy to cloud (Render / Railway)

Add model performance metrics display

Add REST API endpoint

Add user authentication

Add advanced visualizations

👨‍💻 Author

Ayush

Mechanical Engineering Student | ML & Data Science Enthusiast
GitHub: https://github.com/Ayushcdr17

⭐ If You Like This Project

Give it a ⭐ on GitHub!
