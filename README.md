# HR Data Analysis

## Project Overview
This project involves an in-depth analysis of HR data to uncover insights related to employee demographics, attrition, and departmental dynamics. The goal is to understand patterns in employee turnover, demographic distributions, and key correlations within the data.

## Dataset
The analysis utilizes a dataset named `HR Data.csv`, which includes information about employees, their demographics, departmental associations, and attrition status.

## Key Objectives
- Understand employee demographics and departmental distributions.
- Analyze employee turnover and calculate the attrition rate.
- Perform correlation analysis to identify key relationships between variables.
- Visualize data to highlight important trends and insights.

## Tools and Libraries
The project is built using Python with the following libraries:
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Data preprocessing (Label Encoding).

## Data Cleaning & Preprocessing
1. **Column Handling**: Renamed columns to a standardized format (lowercase, underscores).
2. **Missing Values**:
   - Categorical columns filled with mode.
   - Numerical columns filled with the median.
3. **Outlier Treatment**: Used IQR method to cap outliers.
4. **Categorical Encoding**: Applied label encoding to categorical variables for analysis.
5. **Date Formatting**: Converted 'hire_date' column to datetime format.

## Analysis Conducted
### 1. Employee Demographics
- Distribution of employees across different departments and gender.

### 2. Turnover Analysis
- Calculated the attrition rate if 'attrition' column is present.

### 3. Correlation Analysis
- Generated a correlation matrix for numerical features.
- Displayed top 10 correlation pairs using a heatmap.

### 4. Visualization
- Attrition by Department (Bar Chart)
- Attrition by Gender (Bar Chart)
- Age vs Department by Attrition (Boxplot)

## How to Run the Analysis
1. **Clone the repository:**
```sh
git clone <repository_url>
```

2. **Install dependencies:**
```sh
pip install -r requirements.txt
```

3. **Run the analysis script:**
```sh
python hr_data_analysis.py
```

4. **Review the outputs and visualizations** in the console and displayed plots.

## Results & Insights
- Key correlations identified between variables.
- Visualization provided insights into attrition trends by department and gender.
- Outlier treatment ensured robust statistical analysis.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License
This project is licensed under the MIT License.
