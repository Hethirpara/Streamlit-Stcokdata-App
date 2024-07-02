### Stock Information App using Streamlit and yfinance

This Streamlit web application fetches and displays stock information including current price, news, financials, and historical data using the yfinance library.

### How to Use

1. **Installation**:
   - Ensure you have Python installed. This app requires Python 3.6 or later.
   - Install necessary libraries:
     ```
     pip install streamlit yfinance pandas
     ```

2. **Running the App**:
   - Clone the repository or download the `app.py` file.
   - Navigate to the directory containing `app.py` in your terminal or command prompt.
   - Run the app using Streamlit:
     ```
     streamlit run app.py
     ```

3. **Using the App**:
   - Enter a valid stock ticker symbol (e.g., AAPL, MSFT) in the text input box.
   - The app will display:
     - Current stock name and price.
     - Latest stock news with links to read more.
     - Stock financials including income statement, balance sheet, and cash flow.
     - Historical data based on the selected period, displayed both as a table and a line chart.

4. **Selecting Periods**:
   - You can choose different periods (e.g., 1d, 1mo, 1y) from the dropdown to view historical data.

5. **Thank You**:
   - The app concludes with a thank you message.

### Notes

- Ensure a stable internet connection as the app fetches live data from Yahoo Finance.
- Data accuracy and availability depend on Yahoo Finance and may vary.
- This app is intended for demonstration purposes and may require further customization for production use.

### Troubleshooting

- If the app fails to load or displays errors, check your internet connection and ensure all dependencies are installed correctly.

