# Astronomical Data Analysis Project

This project focuses on analyzing astronomical data using Python and various machine learning models to classify different types of stars based on their physical properties. The dataset contains 240 stars with measurements including Temperature (K), Luminosity (L/Lo), Radius (R/Ro), and Absolute magnitude (Mv).

### Dataset Statistics
- Temperature range: 1,939K to 40,000K
- Luminosity range: 0.00008 to 849,420 L/Lo
- Radius range: 0.0084 to 1,948.5 R/Ro
- 6 different star types (0-5)

## Project Structure

- `Soham_Labhshetwar_24095052.ipynb`: Jupyter notebook containing the main analysis code
- `6 class csv.csv`: Dataset file containing astronomical data with features like Temperature, Luminosity, Radius, and Absolute magnitude

## Models and Analysis

The project implements and compares several machine learning models:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)

### Data Processing and Analysis
- Data quality check: No missing values in the dataset
- Feature engineering:
  - Numerical features: Temperature, Luminosity, Radius, Absolute magnitude
  - Categorical features: Star color, Spectral Class
- Data preprocessing:
  - Feature standardization using StandardScaler to normalize the scale of features
  - Train-test split for model evaluation
  - Cross-validation for robust performance assessment
- Data visualization:
  - Statistical analysis of star properties
  - Distribution plots of key features
  - Correlation analysis between different stellar parameters

### Evaluation Metrics
- Classification reports
- Confusion matrices
- Cross-validation scores

## Dependencies

- NumPy: For numerical computations and array operations
- Pandas: For data manipulation and analysis
- Matplotlib & Seaborn: For data visualization
- Scikit-learn: For machine learning models and preprocessing

## Getting Started

1. Ensure you have Python installed on your system
2. Install the required dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```
3. Open the Jupyter notebook to view and run the analysis:
   ```bash
   jupyter notebook Soham_Labhshetwar_24095052.ipynb
   ```

## Author

Soham Labhshetwar
