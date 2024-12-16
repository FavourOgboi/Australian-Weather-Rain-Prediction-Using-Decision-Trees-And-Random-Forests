<div align="center">
  <h1 style="font-size: 3em;">Australian Weather Rain Prediction</h1>
  <h3>Using Decision Trees and Random Forests</h3>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRh_eE3kDp02fYn_fuwXavHzU6XRIeTyoq-yewZ3kse1uuVz6jCwbuez9iLzzeibzGLQec&usqp=CAU" alt="Weather Image" width="500">
</div>

---

## Overview
This project aims to predict whether it will rain tomorrow in various locations across Australia using weather data from the past decade. The analysis utilizes **Decision Trees** and **Random Forests**, leveraging their capabilities for classification tasks.

## Features
- **Dataset:** Daily weather observations for over 10 years from multiple Australian weather stations.
- **Target:** Predict the `RainTomorrow` variable.
- **Models Used:**
  - Decision Tree Classifier
  - Random Forest Classifier
- **Metrics Evaluated:** Accuracy, Precision, Recall, F1-score.

---

## Dataset
The dataset contains weather-related features such as:
- Minimum and maximum temperature
- Rainfall
- Humidity
- Wind speed
- Pressure
- Cloud cover

### Example of Dataset Structure
| Date       | Location  | MinTemp | MaxTemp | Rainfall | RainToday | RainTomorrow |
|------------|-----------|---------|---------|----------|-----------|--------------|
| 2008-12-01 | Melbourne | 14.5    | 25.3    | 0.0      | No        | No           |
| 2008-12-02 | Melbourne | 14.7    | 26.7    | 3.6      | Yes       | Yes          |

---

## Workflow
1. **Data Cleaning:** Handle missing values, encode categorical variables, and scale numerical features.
2. **Exploratory Data Analysis (EDA):** Visualize weather patterns and feature correlations.
3. **Model Training:** Train and evaluate Decision Tree and Random Forest models.
4. **Model Comparison:** Compare metrics to choose the best-performing model.

---

## Results
- **Decision Tree:** Achieved accuracy of 85%.
- **Random Forest:** Outperformed Decision Trees with an accuracy of 90%.

---

## How to Run the Project
### Prerequisites
- Python 3.8+
- Libraries: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`

### Installation
Clone the repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/YourUsername/Australian-Weather-Rain-Prediction-Using-Decision-Trees-and-Random-Forests.git

# Navigate to the project directory
cd Australian-Weather-Rain-Prediction-Using-Decision-Trees-and-Random-Forests

# Install dependencies
pip install -r requirements.txt
```

### Running the Notebook
Open the Jupyter Notebook and run the cells sequentially to:
- Clean and preprocess the data
- Train the models
- Evaluate and visualize results

```bash
jupyter notebook sklearn-decision-trees-random-forests.ipynb
```

---

## Future Improvements
- Add hyperparameter optimization for Random Forest.
- Explore other machine learning models (e.g., Gradient Boosting).
- Integrate weather forecast APIs for real-time predictions.

---

## Contributing
Contributions are welcome! Please create a pull request or open an issue for suggestions.

---

## License
This project is licensed under the MIT License.
