## Insurance Charges Prediction

### Overview
This repository explores a medical insurance charges dataset to predict insurance charges based on various attributes. The project involves data preprocessing, handling missing values, and implementing linear regression models with and without polynomial features.

### Project Structure

- **1. Importing Required Libraries:** Essential Python libraries are imported for data analysis, visualization, and machine learning.

- **2. Loading the Dataset:** The dataset is loaded into a Pandas DataFrame for further analysis.

- **3. Handling Missing Data:** Missing values are addressed for both continuous and categorical attributes. Categorical values are imputed with the most frequent entry, while continuous values are replaced with their mean.

- **4. Data Visualization:** Several visualizations, including regression plots and correlation matrices, are created to understand the relationships between variables.

- **5. Linear Regression Models:** Linear regression models are implemented using Scikit-learn. Both simple and multiple linear regression models are employed to predict insurance charges.

- **6. Ridge Regression with Polynomial Features:** Ridge regression is applied with polynomial features to capture non-linear relationships in the data.

- **7. Data Splitting:** The dataset is split into training and testing sets to evaluate model performance.

### Instructions for Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/insurance-charges-prediction.git
   cd insurance-charges-prediction
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   Open and run the `insurance_charges_prediction.ipynb` notebook for a step-by-step walkthrough of the project.

### Contributors
- Shani Ben Yosef

Feel free to contribute, report issues, or suggest improvements!
