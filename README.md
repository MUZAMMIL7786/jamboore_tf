# jamboore_tf

Jamboree, an ed-tech platform, recently launched a feature allowing students to assess their chances of admission to Ivy League colleges. As a Data Scientist, my task was to develop a machine learning model that predicts the probability of a student gaining admission to an Ivy League college. This journey began with data visualization, exploring a dataset containing 500 rows and 8 columns. Utilizing Seaborn's scatter plots, box plots, and count plots, I conducted thorough univariate and bivariate analyses, shedding light on critical insights.

Data preprocessing involved addressing data quality issues. I tackled duplicates, missing data, and outliers using the robust IQR method. Subsequently, model selection ensued, with a focus on multicollinearity assessment via VIF scores. This led to the removal of two columns. I also tested for homoscedasticity (ensuring p-values > 0.05) and identified Linear Regression and OLSR regression as potential models.

The model's development phase included k-fold cross-validation (k = 4) and a train-test split of 60% for training, 20% for validation, and 20% for testing. To enhance performance, I applied StandardScaler for data standardization and employed Ridge regularization, achieving a commendable R-squared (R^2) score of 77% with OLSR.

Seeking further optimization, I ventured into TensorFlow's Keras library, crafting a neural network with six hidden layers. Leveraging the Rectified Linear Unit (Relu) activation function and the Adam optimizer with a learning rate of 0.01, this effort yielded an impressive accuracy rate of 92%, underscoring the power of deep learning in enhancing predictive capabilities.

## Project Detailed Description

Developed a machine learning model on Jamboree's ed-tech platform to predict Ivy League college admission probabilities for students, achieving a 93% accuracy rate.

- Project Modules:
  - Plan of Process
  - Define Objectives
  - Data Collection
  - Data Cleaning
  - Data Exploration
  - Data Transformation
  - Data Analysis
  - Interpretation of Results
  - Visualization and Reporting
  - Validation and Testing
  - Documentation
  - Conclusion and Recommendations
  - Review and Iteration

 
## Dataset
- Download the dataset for custom training

## Installations
### Requirements
- Python 3.9
- Pandas
- Numpy
- Scikit-Learn
- Seaborn
- Matplotlib


## Contributors
- Peshimaam Mohammed Muzammil
