## ⚙️ Methodology

The project followed a data science workflow covering data understanding, exploratory data analysis, preprocessing, model development, and evaluation.

### 1. Data Understanding and EDA
- Examined the dataset structure, data types, and data quality.
- Analyzed the occupancy class distribution.
- Explored relationships between environmental sensor readings and room occupancy.
- Investigated occupancy patterns over time.

### 2. Data Preprocessing
- Prepared the sensor features and occupancy target.
- Addressed relevant data quality issues.
- Applied appropriate preprocessing while avoiding data leakage.
- Used the selected data-splitting strategy to evaluate model performance.

### 3. Model Development
Two classification models were evaluated:
- **Logistic Regression:** A baseline model for binary classification.
- **Random Forest:** A tree-based model capable of capturing nonlinear relationships and feature interactions.

### 4. Model Evaluation
The models were evaluated using F1-score, precision, recall, accuracy, and a confusion matrix. The evaluation focused on comparing model performance and understanding the trade-offs between different classification errors.

### 5. Feature Interpretation
Environmental sensor features were examined to understand their relationship with occupancy predictions. These relationships represent predictive associations rather than proof of causation.

## 📈 Results and Findings

This section presents the evaluation results of the trained classification models, including their performance metrics, confusion matrices, and key findings from exploratory data analysis.

The final model selection is based on the observed test results and the project's evaluation criteria.
<img width="864" height="352" alt="image" src="https://github.com/user-attachments/assets/5793ed9b-f61d-43ff-b2d5-b77073f8d1ee" />


## 🎥 Project Demo

Watch the **Smart Room Intelligence** demo:

[▶ Watch the Demo Video](https://drive.google.com/file/d/1CkzIlpGRS9wRAHSbgvhi9tm1Q0jMjwnO/view?usp=drivesdk)

## 🚀 Future Improvements

- Explore more advanced time-based occupancy forecasting.
- Extend the dashboard with additional occupancy insights.
- Investigate applications in energy-efficient room management.
- Evaluate the system on additional datasets and real-world sensor data.
