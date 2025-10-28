# CARS24 Cars Data Analysis

This project involves collecting, cleaning, and analyzing data of cars listed on the CARS24 website. The process includes web scraping, data cleaning, and exploratory data analysis (EDA) to uncover pricing trends, popular brands and models, and feature analysis.

---

## Project Workflow

### Step 1: Data Collection (Web Scraping)
- Used **BeautifulSoup** and **requests** to scrape car data from CARS24.
- Extracted key details:
  - **Name/Brand**
  - **Model**
  - **Seater**
  - **Fuel Type**
  - **Safety Ratings**
  - **Mileage**
  - **Price** (max and min)
  - **Extrafeatures**

### Step 2: Data Cleaning
- Removed duplicate entries and handled missing values.
- Converted columns to appropriate data types for consistency.
- Cleaned and standardized categorical and numerical values.

### Step 3: Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Distribution and summary statistics of core automotive features.
- **Bivariate and Multivariate Analysis**: Relationships between variables, such as _Price vs Brand/Model_, _Seaters vs Price_, _Fuel Type vs Price/Safety_, and _Mileage vs Brand/Model_.

### Tools and Libraries Used
- **Python**: Pandas, NumPy
- **Web Scraping**: BeautifulSoup, requests
- **Data Visualization**: Matplotlib, Seaborn
- **Jupyter Notebook**: For interactive data exploration and analysis

---

## Repository Structure

- `CARS24_Data-Analysis_EDA.ipynb`: Jupyter notebook containing all steps from data collection through EDA.
- `cars24_raw_data.csv`: Raw car data collected from CARS24.
- `cars24_cleaned_data.csv`: Cleaned, transformed car data for analysis.
