# Study of Gold Price Prediction and Factors Affecting Gold Prices

This project aims to analyze and predict gold prices using historical data and various economic factors. The system was developed using **Python** with libraries for data analysis, visualization, and machine learning.

---

## Objective

The goal of this study is to explore the relationships between gold prices and key economic indicators such as interest rates, crude oil prices, and currency exchange rates. By leveraging historical data, we aim to build predictive models that provide insights into future price trends.

---

## Scope of the Study

### **1. Gold Price Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: [Sanook Gold Rate](https://www.sanook.com/money/goldrate/)  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Buy Price`: Gold buying price  
    - `Sell Price`: Gold selling price  

### **2. Interest Rate Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: [Bank of Thailand](https://www.bot.or.th/th/statistics/interest-rate.html)  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Savings Rate`: Savings account interest rate  
    - `3-Month Fixed Deposit Rate`  
    - `6-Month Fixed Deposit Rate`  
    - `12-Month Fixed Deposit Rate`  
    - `24-Month Fixed Deposit Rate`  

### **3. Crude Oil Price Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: Yahoo Finance  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Open`: Opening price  
    - `High`: Highest price  
    - `Low`: Lowest price  
    - `Close`: Closing price  
    - `Volume`: Trading volume  
    - `Dividends`: Dividends paid  
    - `Stock Splits`: Stock split events  
    - `Capital Gains`: Capital gains  

### **4. International Gold Stock Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: Yahoo Finance  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Open`: Opening price  
    - `High`: Highest price  
    - `Low`: Lowest price  
    - `Close`: Closing price  
    - `Volume`: Trading volume  
    - `Dividends`: Dividends paid  
    - `Stock Splits`: Stock split events  
    - `Capital Gains`: Capital gains  

### **5. International Gold Fund Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: Yahoo Finance  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Open`: Opening price  
    - `High`: Highest price  
    - `Low`: Lowest price  
    - `Close`: Closing price  
    - `Volume`: Trading volume  
    - `Dividends`: Dividends paid  
    - `Stock Splits`: Stock split events  
    - `Capital Gains`: Capital gains  

### **6. Domestic Gold Fund Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: Yahoo Finance  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Open`: Opening price  
    - `High`: Highest price  
    - `Low`: Lowest price  
    - `Close`: Closing price  
    - `Volume`: Trading volume  
    - `Dividends`: Dividends paid  
    - `Stock Splits`: Stock split events  
    - `Capital Gains`: Capital gains  

### **7. USD to THB Exchange Rate Data**
- **Timeframe**: January 1, 2012 – December 31, 2022  
- **Source**: [Investing.com](https://th.investing.com/currencies/usd-thb-historical-data)  
- **Data Summary**:  
  - Rows: 3652  
  - Columns:  
    - `Date`: Date of the record  
    - `Exchange Rate`: USD to THB exchange rate  

---

## Technology Stack

- **Python**: Core programming language for data processing and analysis
- **Libraries**:  
  - Pandas: Data manipulation and cleaning  
  - NumPy: Numerical computations  
  - Matplotlib & Seaborn: Data visualization  
  - Scikit-learn: Machine learning models for prediction  
  - Yahoo Finance API: Data extraction

---

## Data Analysis and Model Development

1. **Data Cleaning**:  
   Missing and inconsistent values were handled to ensure data integrity.
   
2. **Exploratory Data Analysis (EDA)**:  
   Visualized the relationships between different factors such as gold price trends, oil prices, interest rates, and exchange rates.

3. **Model Building**:  
   Various machine learning models, including Linear Regression and Random Forest, were tested to predict gold prices based on input factors.

---

## Results and Findings

The project report provides a detailed analysis of the results, including model performance, accuracy, and key insights. For a comprehensive overview, please refer to the project documentation.

- **Full Report**: [Project Report](https://drive.google.com/file/d/1VL7JX6_2vZgqI7RkXEvuKyW_5S_Jv7_n/view?usp=share_link)
- **Presentation Slides**: [Project Presentation](./presentation-slide.pdf)

---

## Usage Instructions

1. Clone the repository to your local machine:
   
   git clone [<repository-url>](https://github.com/NarongritPararmard/Study-of-gold-price-prediction-and-factors-affecting-gold-prices.git)

2. Install required Python libraries:

   pip install -r requirements.txt

3. Run the Jupyter Notebook to analyze the data:

   jupyter notebook Project.ipynb

## Contributions

Contributions are welcome! If you have ideas for improving the project, feel free to fork the repository and submit a pull request.
