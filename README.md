# weather_forecasting
**Weather Forecasting Model** — A machine learning project that predicts next-day temperature using historical weather data. It applies Linear Regression with key weather parameters like temperature, humidity, wind speed, and precipitation, evaluates model accuracy, and visualizes actual vs predicted results.

# 🌦️ Weather Forecasting Using Machine Learning

A machine learning-based weather forecasting system that predicts the next day's temperature using historical weather data. The project uses **Linear Regression** to analyze relationships between temperature, humidity, wind speed, and precipitation to generate accurate temperature predictions.

---

## 📌 Project Overview

Weather forecasting plays an important role in planning and decision-making across various industries. This project demonstrates a simple machine learning approach for predicting future temperature values from historical weather patterns.

The model is trained using weather parameters and evaluated using regression performance metrics. It also provides a visualization comparing actual and predicted temperatures.

---

## 🚀 Features

- Generate synthetic historical weather datasets
- Train a Linear Regression prediction model
- Predict next-day temperature
- Evaluate model performance using:
  - Mean Squared Error (MSE)
  - R² Score
- Compare actual vs predicted temperatures visually
- Simple and beginner-friendly ML workflow

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data processing and analysis
- **Scikit-learn** – Machine learning model development
- **Matplotlib** – Data visualization

---

## 📂 Project Structure

```
Weather-Forecasting/
│
├── dataset_generator.py       # Generates the weather dataset
├── weather_forecasting.py     # Main machine learning implementation
├── temprature.csv             # Generated weather dataset
├── requirements.txt           # Required Python dependencies
└── README.md                  # Project documentation
```

---

## 📊 Dataset Description

The dataset contains historical weather observations used for training the machine learning model.

### Features:

| Feature | Description |
|---------|-------------|
| Temperature | Current temperature in °C |
| Humidity | Percentage of humidity |
| Wind Speed | Wind speed measurement |
| Precipitation | Rainfall amount |
| Next Day Temperature | Target value to predict |

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-forecasting.git
```

### 2. Navigate to the project directory

```bash
cd weather-forecasting
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Step 1: Generate Dataset

Run the dataset generator:

```bash
python dataset_generator.py
```

This will create the required `temprature.csv` dataset.

### Step 2: Train and Test the Model

Run the forecasting model:

```bash
python weather_forecasting.py
```

The program will:
- Load historical weather data
- Train a Linear Regression model
- Evaluate model accuracy
- Display actual vs predicted temperature values
- Predict the next day's temperature

---

## 🧠 Machine Learning Workflow

1. Load weather dataset
2. Select input features:
   - Temperature
   - Humidity
   - Wind Speed
   - Precipitation
3. Split data into training and testing sets
4. Train Linear Regression model
5. Generate predictions
6. Evaluate model performance
7. Visualize prediction results

---

## 📈 Model Evaluation

The model performance is measured using:

### Mean Squared Error (MSE)
Measures the average squared difference between actual and predicted temperatures.

### R² Score
Indicates how well the model explains variations in temperature data.

Higher R² values represent better prediction performance.

---

## 📷 Output Visualization

The project generates a comparison graph showing:

- Actual temperature values
- Predicted temperature values

This helps analyze the accuracy and behavior of the forecasting model.

---

## 🔮 Example Prediction

Given weather conditions:

```
Temperature: 30°C
Humidity: 60%
Wind Speed: 10 km/h
Precipitation: 0
```

The trained model predicts the expected temperature for the following day.

---

## 🔮 Future Improvements

- Integrate real-time weather APIs
- Use larger real-world datasets
- Implement advanced models:
  - Random Forest Regression
  - XGBoost
  - Neural Networks
- Add multi-day forecasting capability
- Develop a web-based weather prediction interface

---

## 👨‍💻 Author

**Abhinav Dixit**

---

## 📄 License

This project is licensed under the MIT License.
