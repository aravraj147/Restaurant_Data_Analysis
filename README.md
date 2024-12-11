# Data Preprocessing and Analysis Steps

## Key Steps Involved

### 1. Identify Missing Values
- Check for missing values in key columns:
  - **Country code**
  - **City**
  - **Address**

### 2. Fill Missing Data
- Use appropriate techniques for filling missing data:
  - **Numerical columns**: Use mean, median, or mode.
  - **Categorical columns**: Use the most frequent value or a placeholder like "NAN".
  - **Excessive missing data**: Drop rows or columns if necessary.

### 3. Data Cleaning
- Remove duplicate rows:
  - For example, duplicates in **Locality Verbose** and **Locality** columns.
- Fix inconsistent formatting:
  - Example: Convert "Address :: ..??" to "Address :: ...".
- Standardize date formats:
  - Convert formats like **"MM/DD/YYYY"** to **"YYYY-MM-DD"**.
- Correct spelling errors in categorical data:
  - Example: "Burgers" vs "Burgerz".
- Normalize text fields:
  - Use lowercase for fields like **customer reviews** or **food item descriptions**.

### 4. Feature Engineering
- **Aggregate Rating**:
  - Visualize distribution using seaborn.
- **Categorical Columns**:
  - Analyze the distribution of categorical data.
- **Top Cuisines and Cities**:
  - Identify top cuisines and cities with restaurants.
- **Restaurant Distribution**:
  - Analyze the distribution of restaurants across different cities.
- **Correlation Analysis**:
  - Investigate the correlation between a restaurant's location and its rating.

### 5. Multiple Analyses on Different Parameters
- Perform in-depth analysis across various parameters to extract insights.
