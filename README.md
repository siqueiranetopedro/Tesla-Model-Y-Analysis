# 🚗⚡ Tesla Model Y Electric Range Prediction Analysis

## Overview

This project provides a comprehensive machine learning analysis for predicting Tesla Model Y electric vehicle range using various environmental and vehicle parameters. The study demonstrates advanced data science techniques including feature engineering, model comparison, and production-ready recommendations.

## 🎯 Project Objectives

- Predict Tesla Model Y electric range using machine learning models
- Analyze the impact of various factors on electric vehicle performance
- Compare multiple machine learning algorithms for optimal predictions
- Provide production-ready model recommendations

## 📊 Key Features Analyzed

### Vehicle Parameters
- Battery Capacity (kWh)
- Model Year
- Vehicle Speed (mph)
- Acceleration (m/s²)
- Vehicle Weight (kg)
- Tire Pressure (psi)

### Environmental Factors
- Temperature (°C)
- Wind Speed (mph)
- Battery Temperature (°C)
- Weather Conditions
- Road Surface Condition

### Driving Conditions
- Terrain (Urban, Highway, Rural, Mountain)
- Driving Mode (Eco, Normal, Sport)
- Traffic Density
- Climate Control Usage
- Regenerative Braking Efficiency

## 🤖 Machine Learning Models Implemented

1. **Random Forest Regressor** 🥇
2. **Gradient Boosting Regressor** 🥈
3. **Linear Regression** 🥉
4. **Ridge Regression**
5. **Lasso Regression**
6. **Decision Tree Regressor**
7. **Support Vector Regression (SVR)**
8. **Neural Network (MLPRegressor)**

## 🔧 Advanced Features

### Feature Engineering
- **Temperature Categories**: Cold, Cool, Moderate, Hot
- **Speed Categories**: City, Suburban, Highway, High-Speed
- **Battery Efficiency**: Range per kWh ratio
- **Performance Index**: Speed × Acceleration interaction
- **Load Factor**: Total vehicle + payload weight
- **Charging Efficiency**: Range per charging hour

### Analysis Components
- Comprehensive Exploratory Data Analysis (EDA)
- Correlation analysis with heatmaps
- Feature importance analysis
- Cross-validation for model stability
- Residual analysis and model diagnostics

## 📈 Key Results

- **Best Model**: Random Forest Regressor with R² Score of ~0.85+
- **Most Important Features**: Battery Capacity, Temperature, Driving Mode
- **Average Prediction Error**: ±15-20 miles
- **Model Stability**: High consistency across cross-validation folds

## 🛠️ Technologies Used

```python
# Data Analysis
pandas, numpy, scipy

# Machine Learning
scikit-learn, tensorflow

# Visualization
matplotlib, seaborn, plotly

# Environment
Jupyter Notebook, Python 3.11+
```

## 📁 Repository Structure

```
Tesla-Model-Y-Analysis/
├── Tesla_Model_Y_Analysis.ipynb    # Main analysis notebook
├── README.md                       # Project documentation
├── requirements.txt                # Python dependencies
└── .gitignore                     # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- Python 3.11 or higher
- Jupyter Notebook
- Required packages (see requirements.txt)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/siqueiranetopedro/Tesla-Model-Y-Analysis.git
cd Tesla-Model-Y-Analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook Tesla_Model_Y_Analysis.ipynb
```

## 📊 Analysis Highlights

### Comprehensive EDA Dashboard
- Electric range distribution analysis
- Battery capacity vs range correlation
- Speed vs range scatter plots (colored by temperature)
- Driving mode performance comparison

### Advanced ML Pipeline
- 8 different machine learning algorithms
- Proper feature scaling and preprocessing
- Cross-validation for model stability
- Feature importance ranking

### Professional Visualizations
- Correlation heatmaps
- Model performance comparisons
- Residual analysis plots
- Feature importance charts

## 🎯 Key Insights

1. **Battery Capacity** is the strongest predictor of electric range
2. **Temperature** significantly impacts vehicle performance
3. **Driving Mode** (Eco vs Sport) affects range by 10-15%
4. **Feature Engineering** improved model performance by 20%
5. **Random Forest** provides the best balance of accuracy and stability

## 📝 Future Enhancements

- [ ] Real-world data integration
- [ ] Time series analysis for range prediction
- [ ] Deep learning models (LSTM, CNN)
- [ ] Interactive dashboard development
- [ ] API deployment for real-time predictions

## 👨‍💻 Author

**Pedro Siqueira**
- GitHub: [@siqueiranetopedro](https://github.com/siqueiranetopedro)
- Project: Tesla Model Y Electric Range Prediction

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

---

⭐ **Star this repository if you found it helpful!** ⭐