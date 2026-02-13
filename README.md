# 🚗 Cars Price Analysis - Data Exploration & Visualisation

**University of Hertfordshire - Data Science Assignment**  
**Course**: Data Exploration & Visualisation  
**Assignment Weight**: 35%  
**Due Date**: 13 February 2026

---

## 📋 Project Overview

This project performs comprehensive **Exploratory Data Analysis (EDA)** on a cars price dataset containing 8,128 car listings. The analysis includes data preprocessing, statistical analysis, correlation studies, and multiple types of visualizations to uncover insights about factors affecting car prices.

### 🎯 Key Objectives:
- Perform data cleaning and preprocessing
- Generate descriptive statistics
- Conduct correlation analysis
- Create professional visualizations (Statistical, Relational, Categorical)
- Communicate insights through data-driven storytelling

---

## 📊 Dataset Information

- **Filename**: `cars_price.csv`
- **Records**: 8,128 car listings
- **Features**: 12 variables
  - `name`: Car model name
  - `year`: Manufacturing year
  - `selling_price`: Selling price (₹)
  - `km_driven`: Kilometers driven
  - `fuel`: Fuel type (Petrol, Diesel, CNG, LPG, Electric)
  - `seller_type`: Type of seller
  - `transmission`: Transmission type (Manual, Automatic)
  - `owner`: Ownership status
  - `mileage(km/ltr/kg)`: Fuel efficiency
  - `engine`: Engine capacity (CC)
  - `max_power`: Maximum power (bhp)
  - `seats`: Number of seats

---

## 🛠️ Technologies Used

### Programming Language:
- **Python 3.8+**

### Libraries:
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scipy** - Scientific computing and statistics
- **scikit-learn** - Machine learning utilities

---

## 📁 Project Structure

```
cars-price-analysis/
│
├── Cars_Price_Analysis_Complete.ipynb  # Main Jupyter Notebook (Google Colab compatible)
├── cars_analysis.py                     # Python script version
├── cars_price.csv                       # Dataset
├── README.md                            # Project documentation
│
├── plots/                               # Generated visualizations
│   ├── 01_correlation_heatmap.png
│   ├── 02_price_distribution.png
│   ├── 03_scatter_relationship.png
│   ├── 04_categorical_analysis.png
│   ├── 05_pairplot.png
│   ├── 06_count_by_category.png
│   ├── 07_multi_scatter.png
│   └── ... (additional plots)
│
└── presentation/                        # Presentation materials
    ├── Cars_Price_Analysis.pptx        # PowerPoint presentation
    └── presentation_video.mp4          # Video presentation
```

---

## 🚀 Getting Started

### Option 1: Google Colab (Recommended)

1. **Open the notebook in Google Colab**:
   - Click the "Open in Colab" button or
   - Upload `Cars_Price_Analysis_Complete.ipynb` to Google Colab

2. **Upload the dataset**:
   ```python
   from google.colab import files
   uploaded = files.upload()  # Upload cars_price.csv
   ```

3. **Run all cells**:
   - Go to `Runtime` → `Run all`

### Option 2: Local Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/[your-username]/cars-price-analysis.git
   cd cars-price-analysis
   ```

2. **Install required packages**:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
   ```

3. **Run the notebook**:
   ```bash
   jupyter notebook Cars_Price_Analysis_Complete.ipynb
   ```

### Option 3: Python Script

```bash
python cars_analysis.py
```

---

## 📊 Analysis Workflow

### 1. Data Preprocessing (30%)
- ✅ **Data Cleaning**:
  - Removed duplicates
  - Handled missing values (median for numeric, mode for categorical)
  - Outlier detection and removal using IQR method
  - Data type conversions

- ✅ **Feature Engineering**:
  - Created `car_age` feature
  - Created `price_category` feature

- ✅ **Descriptive Statistics**:
  - Summary statistics for numeric variables
  - Frequency distributions for categorical variables
  - Skewness and kurtosis analysis

- ✅ **Correlation Analysis**:
  - Pearson correlation matrix
  - Identified highly correlated variable pairs
  - Analyzed features correlated with selling price

### 2. Visualizations (20%)

#### Statistical Plots (6%):
1. **Correlation Heatmap** - Shows relationships between all numeric variables
2. **Price Distribution Analysis** - Histogram, box plot, Q-Q plot, violin plot
3. **Feature Importance** - Correlation with selling price

#### Relational Plots (7%):
4. **Scatter Plot with Regression** - Year vs Price relationship
5. **Multi-Variable Scatter** - km_driven vs Price by Fuel type
6. **Pairplot** - Pairwise relationships between numeric variables

#### Categorical Plots (7%):
7. **Fuel Type Analysis** - Count plot, bar plot, box plot, violin plot
8. **Transmission Analysis** - Bar plot with error bars, swarm plot
9. **Year-wise Trends** - Line plots and dual-axis charts
10. **Comprehensive Dashboard** - Multiple insights in one view

### 3. Key Insights

Based on the analysis, key findings include:

- **Price Trends**: Newer cars (2015+) command significantly higher prices
- **Fuel Type Impact**: Diesel cars have the highest average price
- **Transmission**: Automatic transmission cars are priced higher on average
- **Mileage Effect**: Higher km_driven correlates with lower prices (negative correlation)
- **Strong Correlations**: Year and engine size show moderate positive correlation with price

---

## 📈 Sample Visualizations

### Correlation Heatmap
Shows the relationships between all numeric variables in the dataset.

### Price Distribution
Multi-panel visualization showing histogram, box plot, Q-Q plot, and violin plot of selling prices.

### Categorical Analysis
Comprehensive analysis of categorical variables with multiple visualization types.

---

## 🎓 Assignment Requirements Met

### Data Preprocessing & EDA (30%):
- ✅ Data cleaning & preparation (10%)
- ✅ Descriptive statistics (10%)
- ✅ Correlation & EDA depth (10%)

### Python Coding (30%):
- ✅ Modular code structure (10%) - Each plot has its own dedicated function
- ✅ Code quality and documentation (10%) - Comprehensive docstrings and comments
- ✅ Correctness of graph implementation (10%) - All graphs work correctly

### Visualizations (20%):
- ✅ Relational plot (7%) - Scatter plots, pairplot
- ✅ Categorical plot (7%) - Bar charts, box plots, violin plots
- ✅ Statistical plot (6%) - Correlation heatmap, distribution plots

### Insights & Presentation (20%):
- ✅ Comprehensive insights extracted and documented
- ✅ Clear and professional code structure
- ✅ Ready for PowerPoint presentation creation

---

## 📝 How to Use This Code for Your Assignment

1. **Download/Clone** this repository
2. **Customize** the code with your own name and student ID
3. **Run** the notebook and generate all visualizations
4. **Create** your PowerPoint presentation using the generated plots
5. **Upload** to your own GitHub repository
6. **Record** your 10-minute presentation video
7. **Submit** via Blackboard

---

## 🤝 Contributing

This is an educational project for assignment submission. However, suggestions and improvements are welcome!

---

## 📄 License

This project is created for educational purposes as part of the University of Hertfordshire coursework.

---

## 👤 Author

**Samsul Jahith S**  
Student ID:  8232ESLG 
University of Hertfordshire  
School of Physics, Engineering and Computer Science

---

## 📞 Contact

For questions or collaboration:
- Email: samsuljahith@gmail.com
- GitHub: https://github.com/samsuljahith

---

## 🙏 Acknowledgments

- University of Hertfordshire for the assignment framework
- Tutor: Wong Kim Siong
- Dataset source: cars_price.csv (Assignment dataset)
- Python community for excellent data science libraries

---

## 📚 References

1. McKinney, W. (2017). *Python for Data Analysis*. O'Reilly Media.
2. VanderPlas, J. (2016). *Python Data Science Handbook*. O'Reilly Media.
3. Pandas Documentation: https://pandas.pydata.org/docs/
4. Seaborn Documentation: https://seaborn.pydata.org/
5. Matplotlib Documentation: https://matplotlib.org/

---

**Last Updated**: February 2026

**Status**: ✅ Ready for Submission

---

*This README was generated as part of the Data Exploration & Visualisation assignment at the University of Hertfordshire.*
