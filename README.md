# 🌦️ Weather Forecasting Model

A Machine Learning project that predicts future weather patterns using historical weather data. This project focuses on forecasting the next day's temperature by analyzing features such as humidity, wind speed, atmospheric pressure, and precipitation. It demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

---

## 📌 Table of Contents

- Overview
- Features
- Technologies Used
- Dataset
- Project Structure
- Workflow
- Machine Learning Model
- Results
- Installation
- Usage
- Future Improvements
- Author
- License

---

# 📖 Overview

Weather forecasting is one of the most important real-world applications of Machine Learning. By analyzing historical weather records, the model learns patterns and relationships between weather parameters to predict future temperature values.

This project performs:

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Selection
- Model Training
- Model Evaluation
- Future Temperature Prediction
- Data Visualization

---

# ✨ Features

- Historical weather data analysis
- Data preprocessing and cleaning
- Feature engineering
- Correlation analysis
- Temperature prediction using Machine Learning
- Performance evaluation using multiple metrics
- Visualization of prediction results
- Beginner-friendly implementation
- Google Colab compatible

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Dataset

The project uses a historical weather dataset containing weather observations such as:

- Date
- Temperature
- Humidity
- Wind Speed
- Atmospheric Pressure
- Precipitation
- Weather Condition

Dataset Source:

https://www.kaggle.com/datasets/budincsevity/szeged-weather

---

# 📁 Project Structure

```
Weather-Forecasting-Model/
│
├── data/
│   └── weather.csv
│
├── notebooks/
│   └── Weather_Forecasting_Model.ipynb
│
├── images/
│   ├── dataset_overview.png
│   ├── correlation_heatmap.png
│   └── prediction_graph.png
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# ⚙️ Workflow

```
Historical Weather Data
            │
            ▼
     Data Preprocessing
            │
            ▼
 Exploratory Data Analysis
            │
            ▼
    Feature Selection
            │
            ▼
      Train-Test Split
            │
            ▼
 Model Training (Random Forest)
            │
            ▼
      Model Prediction
            │
            ▼
 Performance Evaluation
            │
            ▼
 Future Weather Prediction
```

---

# 🤖 Machine Learning Model

This project uses the **Random Forest Regressor** algorithm.

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### Why Random Forest?

- High prediction accuracy
- Handles non-linear relationships
- Works well with numerical data
- Less prone to overfitting
- Minimal preprocessing required

---

# 📊 Exploratory Data Analysis

The following analyses are performed:

- Missing Value Analysis
- Statistical Summary
- Feature Distribution
- Correlation Heatmap
- Temperature Distribution
- Humidity Analysis
- Wind Speed Analysis

---

# 📈 Model Evaluation

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help determine how accurately the model predicts future temperatures.

---

# 📷 Output Visualizations

The project includes visualizations such as:

- Dataset Overview
- Correlation Heatmap
- Actual vs Predicted Temperature Graph
- Feature Importance Graph (Optional)

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Weather-Forecasting-Model.git
```

Move into the project directory

```bash
cd Weather-Forecasting-Model
```

Install required libraries

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

1. Download the weather dataset.
2. Place the dataset inside the `data` folder.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run all cells in sequence.
5. View the prediction results and generated graphs.

---

# 📊 Expected Results

The model predicts the next day's temperature based on historical weather conditions.

Expected performance (may vary depending on the dataset):

| Metric | Expected Value |
|---------|---------------|
| MAE | ~1–2°C |
| RMSE | ~2–3°C |
| R² Score | 0.90+ |

---

# 📌 Applications

- Weather Forecasting
- Agriculture
- Smart Farming
- Disaster Management
- Climate Research
- Energy Planning
- Environmental Monitoring

---

# 🔮 Future Improvements

- Deep Learning using LSTM
- Rainfall Prediction
- Weather Classification
- 7-Day Weather Forecasting
- Real-Time Weather API Integration
- Streamlit Web Application
- Model Deployment using Flask
- Hyperparameter Tuning
- Feature Importance Analysis

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

**Khushi Gupta**

B.Tech Computer Science & Engineering (Artificial Intelligence & Machine Learning)

GLA University

GitHub: https://github.com/your-username

LinkedIn: https://www.linkedin.com/in/your-linkedin-profile/

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub. It helps others discover the project and motivates further improvements.

Happy Coding! 🚀<img width="1000" height="500" alt="prediction_graph" src="https://github.com/user-attachments/assets/a18b2294-e0bf-4ee9-a4f9-860565315c09" />
