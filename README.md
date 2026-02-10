# Flipkart-phone-data--EDA-analysis
Web scraping and analysis of phone data from Flipkart

## 📊 Project Overview
This project involves web scraping phone data from Flipkart, followed by data cleaning and exploratory data analysis (EDA).

## 🛠️ Technologies Used
- Python 3
- Jupyter Notebook
- pandas
- BeautifulSoup
- requests
- matplotlib
- re (regex)

## 📁 Files
- `L2.ipynb` - Main Jupyter Notebook with all code
- `phone.csv` - Raw scraped data
- `cleaned_phone_data.csv` - Cleaned dataset

## 🔍 Project Steps
1. **Web Scraping**: Extracted phone data from Flipkart (240 records)
2. **Data Storage**: Saved raw data to CSV
3. **Data Cleaning**: 
   - Handled missing values
   - Removed outliers
   - Extracted numerical values from text columns
   - Standardized text format
4. **Exploratory Data Analysis**:
   - Statistical summaries
   - Visualization of price distribution
   - Analysis of ratings, memory, battery, etc.

## 📈 Key Insights
- Analyzed 133 cleaned phone records
- Price range: ₹5,999 - ₹29,999
- Average rating: 4.31/5
- Memory configurations from 3GB to 8GB

## 🚀 How to Run
1. Clone this repository
2. Install requirements: `pip install pandas requests beautifulsoup4 matplotlib`
3. Open `L2.ipynb` in Jupyter Notebook
4. Run cells sequentially

## 📝 Note
The data was collected for educational purposes only.
