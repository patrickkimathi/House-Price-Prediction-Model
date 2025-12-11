🏡 House Price Prediction – Linear Regression Model
A Machine Learning Regression Project by Patrick Kimathi Kariuki

📌 Project Overview
This project builds a Linear Regression model to predict house prices based on area (in square feet). 
The goal is to demonstrate the full machine learning pipeline—from data loading and exploration to model training, evaluation, and visualization.

The model achieves strong results with an R² score of ~0.92, indicating excellent fit for the dataset.

📂 Features
✔ Data loading and preprocessing
✔ Exploratory Data Analysis (EDA)
✔ Scatterplots (Area vs Price)
✔ Train–test split
✔ Linear Regression model with Scikit-Learn
✔ Model performance metrics
✔ Regression line visualization
✔ Exporting dataset for reuse

🧰 Technologies Used

Python 3.10+
Pandas – data manipulation
NumPy – numerical operations
Matplotlib & Seaborn – visualization
Scikit-Learn – machine learning

🛠 Installation Instructions
1. Clone the repository
git clone https://github.com/your-username/house-price-regression.git
cd house-price-regression

2. Create & activate a virtual environment
python -m venv venv
source venv/bin/activate     # Linux/Mac
venv\Scripts\activate        # Windows

3. Install dependencies
pip install -r requirements.txt

▶ Running the Project
Run the script
python patrick_kariuki_cyber_shujaa_task_regression_model.py

Or open the Jupyter Notebook
jupyter notebook

📈 Model Performance
Metric	Score
MSE	Low (good)
RMSE	Low (good)
R² Score	~0.92

A high R² value indicates that the model captures most of the variance in house prices based on area.

📊 Visualizations
The script generates useful plots:
Scatter plot (Area vs Price)
Train split scatter plot
Test split scatter plot
Regression line vs Actual data

🧠 Key Insights
House price increases linearly with area.
Model generalizes well to unseen test data.
Additional features (location, rooms, age) could improve prediction accuracy.

📦 Dataset

The project uses homeprices.csv, which contains:
area – size of house (sq ft)
price – selling price in USD

📝 License

This project is licensed under the MIT License.

👤 Author

Patrick Kimathi Kariuki
Data Analyst | Python | SQL | Power BI
LinkedIn: https://linkedin.com/in/patkariuki
Email: patkimathi148@gmail.com

📬 Contributions
Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to improve.
