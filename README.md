# CodeAlpha_Sales_Prediction
📊 Sales Prediction Dashboard Using Python
📌 Project Overview

Sales Prediction Dashboard is a Machine Learning project that predicts sales based on advertising expenditure across TV, Radio, and Newspaper platforms.

The project uses a Random Forest Regression algorithm and an interactive Streamlit dashboard to generate sales predictions and visualize advertising impact.

🛠️ Technologies Used
Python 3.12
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Streamlit
Plotly
Jupyter Notebook
🤖 Machine Learning Algorithm

Random Forest Regressor

Evaluation metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared (R²)
✨ Dashboard Features
Interactive home dashboard.
TV, Radio, and Newspaper advertising budget inputs.
Real-time sales prediction.
Advertising budget distribution pie chart.
Sales scenario comparison bar chart.
Interactive data visualization.
Project information page.
📂 Project Structure
text
Sales Prediction Using Python/
│
├── Advertising.csv
├── app.py
├── Sales_Prediction_With_Advertisement_.ipynb
├── sales_model.pkl
├── sales_prediction_model.pkl
├── sales_feature_names.pkl
└── README.md

⚙️ Installation and Setup
1. Create Virtual Environment
bash
py -3.12 -m venv sales_env

2. Activate Virtual Environment
bash
sales_env\Scripts\activate

3. Install Required Libraries
bash
pip install scikit-learn==1.6.1 joblib pandas numpy matplotlib seaborn streamlit plotly

4. Run the Application
bash
python -m streamlit run app.py

5. Open in Browser
text
http://localhost:8501

📈 Project Objective

The main objective is to analyze advertising expenditure and predict sales using Machine Learning techniques.

The dashboard helps users understand how advertising investments influence predicted sales.

📊 Model Evaluation

The model uses the following performance metrics:

MAE
MSE
R² Score
🚀 Future Enhancements
Compare multiple Machine Learning algorithms.
Improve model accuracy through hyperparameter tuning.
Add more interactive visualizations.
Deploy the dashboard online.
Include additional business analytics features.
📝 Conclusion

This project demonstrates how Machine Learning can be used for sales forecasting and advertising analysis.

By combining Random Forest Regression, Python, Streamlit, and Plotly, the project provides an interactive platform for sales prediction and data visualization.

Project Name: Sales Prediction Dashboard Using Python

Domain: Machine Learning / Data Science

Algorithm: Random Forest Regression

Framework: Streamlit

Visualization: Plotly

#Run Command
sales_env\Scripts\activate
python -m streamlit run app.py

