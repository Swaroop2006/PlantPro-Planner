# PlantPro-Planner
PlantPro Planner is a crop recommendation web app using machine learning. It suggests the best crop to grow based on soil nutrients, pH, temperature, humidity, and rainfall. Built with Python (Flask) and scikit-learn for ML predictions. Easy-to-use interface for farmers and agri-researchers.
📌 Features
Suggests the best crop based on:

Nitrogen (N), Phosphorus (P), and Potassium (K) levels

Temperature in °C

Humidity percentage

Soil pH value

Rainfall in mm

Utilizes a trained machine learning model for accurate recommendations

Provides a clean and responsive web interface built using Flask

Includes support for both MinMaxScaler and StandardScaler scaling methods

📁 Project Structure
The project contains:

app.py – Flask application backend

templates/ – HTML frontend (mainly index.html)

static/ – Static assets like CSS or images

model.pkl – Trained ML model file

minmaxscaler.pkl and standscaler.pkl – Scaler objects used for preprocessing

Crop Recommendation Using Machine Learning.ipynb – Jupyter notebook used for model training

Crop_recommendation.xls – Dataset containing environmental data and crop labels

README.md – Project documentation

🧠 Machine Learning Details
The model is trained using environmental and soil features to predict the most suitable crop. These features include:

Soil nutrients: Nitrogen, Phosphorus, Potassium

Weather data: Temperature, Humidity, Rainfall

Soil pH

A classification algorithm (like Random Forest or similar) is used to train the model and generate accurate predictions.

🌾 Use Cases
Assists farmers in identifying crops best suited for their local conditions

Useful for agritech startups and agricultural research projects

Helpful for students learning machine learning with real-world datasets

📸 Screenshot
A screenshot of the app shows a form to input soil and climate data. After clicking "Get Recommendation", the app displays the best crop to grow based on the entered values.

![Screenshot 2025-07-04 184720](https://github.com/user-attachments/assets/4b6b1835-c431-498e-9b37-84fedf596e15)

![Screenshot 2025-07-04 184813](https://github.com/user-attachments/assets/11e05237-9672-4bb2-a6fa-1421d9bd3512)

