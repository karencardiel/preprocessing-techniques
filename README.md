# Gender Inequality Data Preprocessing

This project involves cleaning and preprocessing the `gender_inequality_index.csv` dataset, which contains indicators of gender inequality across various countries. The objective is to prepare the data for analysis and gain meaningful insights into factors affecting gender inequality worldwide.

## Features

- **Data Cleaning:** Handling missing values, removing duplicates, and dropping irrelevant columns.
- **Data Transformation:** Converting columns to numeric types for analysis.
- **Feature Engineering:** Creating new features, such as the maternal mortality to adolescent birth rate ratio.
- **Data Visualization:** Generating histograms, boxplots, scatter plots, and correlation matrices.
- **Export Processed Data:** Saving the cleaned data into a new CSV file for further analysis.

## Requirements

- **Python Version:** 3.8 or higher
- **Libraries:** 
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `google.colab` (for Google Drive integration)

## How to Run

### Option 1: Run on Google Colab

You can run the project directly on Google Colab using the link below:

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SOsZwAiIZhTIvcKijrnvOh2tTXpAQFkM?usp=sharing)

### Option 2: Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gender-inequality-data-cleaning.git
   cd gender-inequality-data-cleaning
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Execute the main script:

   ```bash
   python data_cleaning.py
   ```

## Preprocessing steps

1. **Loading data:** Access the dataset from Google Drive using `google.colab` or load it locally.
2. **Inspecting data:** Examine the dataset structure, column types, and initial rows.
3. **Cleaning:** 
   - Replace placeholder values (`'..'`) with `NaN`.
   - Drop missing rows and irrelevant columns.
   - Remove duplicate rows based on the `HDI rank`.
4. **Transforming data:**
   - Convert columns to numeric types for calculations.
   - Create a new feature: maternal mortality to adolescent birth rate ratio.
   - Bin the ratio into categories for better visualization.
5. **Visualization:** 
   - Explore trends using histograms, boxplots, scatter plots, and heatmaps.
6. **Export Processed Data:** Save the cleaned dataset into a new CSV file.

## Results

- [Raw Dataset](https://drive.google.com/file/d/1CiqAWk4ipx-cN7DToHQfgd7Fok3_R0We/view?usp=sharing)
- [Cleaned Dataset](https://drive.google.com/file/d/1_zOdTwhoaZr71-y8biTpvpLAMI22aLUi/view?usp=sharing)

## Example visualizations

1. **Histogram:** Distribution of seats held by women in parliament.  
2. **Boxplot:** Female secondary education percentages across countries.  
3. **Count Plot:** Binned ratio of maternal mortality to adolescent birth rate.  
4. **Scatter Plot:** Relationship between female and male secondary education.  
5. **Correlation Matrix:** Relationships among socioeconomic and health indicators.

## Contributors

- **Karen Cardiel Olea**  
- **Elisabet Arelly Sulú Vela**  
- **Professor:** Lester Stephan Estrada López 
- **Institution:** Universidad Politécnica de Yucatán
- **Asignature:** Data Preprocessing

**Submission date:** October 23, 2024  

---

**Note:** This project was developed as part of an academic assignment. We hope it serves as a useful reference for learning data preprocessing techniques and exploring gender inequality analysis.
