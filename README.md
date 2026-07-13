🏡HOUSE PRICE PREDICTION USING MACHINE LEARNING:
A beginner-friendly project to predict house prices based on various factors such as square footage, number of bedrooms, location, and more. This project walks through data exploration, linear regression, and gradient boosting to compare model performance.

📂 PROJECT STRUCTURE:
-data/:Dataset used for training and testing
-house_price_prediction.ipynb:Main Jupyter Notebook with all code
-requirements.txt:Python dependencies
-README.md:Project documentation

📊DATASET:

King County House Sales dataset — contains details of house listings including:
- Number of bedrooms and bathrooms
- Square footage (with and without basement)
- Waterfront presence
- Location via latitude and longitude
- Zipcode
- Year built and renovated
- Price of the house

SOURCE: [Kaggle - House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

🧪MODELS USED:
🔹LINEAR REGRESSION:
- Baseline model to understand relationships in the data
- Achieved ~70% (R² = 0.70) accuracy

🔹GRADIENT BOOSTING REGRESSOR:
- Ensemble model using decision trees
- Achieved ~87% (R² = 0.87) accuracy

🔧REQUIREMENTS:
Install dependencies using:
pip install -r requirenments.txt

MAIN LIBRARIES USED:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

🚀HOW TO RUN:

Clone the repository:
git clone https://github.com/avanikumar/house-price-prediction.git
cd house-price-prediction

Install dependencies:
pip install -r requirenments.txt

Run the Jupyter Notebook:
jupyter notebook house_price_prediction.ipynb

📚LEARNING POINTS:
- Data cleaning and preprocessing
- Train/test splitting
- Linear Regression vs Gradient Boosting
- Model evaluation using `r2_score`

🌟CONTRIBUTE:
Feel free to fork this project, improve the model, or apply it to other real estate datasets!
