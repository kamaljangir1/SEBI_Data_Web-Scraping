# SEBI Portfolio Managers Data Scraping Project

## Description
This project involves web scraping data from the SEBI website to collect information about 512 portfolio managers, each with 112 columns of data. The data pertains to portfolio managers' performance and other relevant metrics for June 2024. After scraping the data using Python, the information is stored and organized in an Excel file. The data is further processed in Excel, including formatting and calculations using VLOOKUP and other functions.

## Tech Stack
- **Python**: Used for web scraping and data collection.
- **Excel**: Used for data organization, formatting, and calculations.

## Data Scraped
- **Source**: SEBI Website : https://www.sebi.gov.in/sebiweb/other/OtherAction.do?doPmr=yes
- **Data**: Information about 512 portfolio managers with 112 columns each.

## Steps and Methodology

### Web Scraping
1. **Python Libraries Used**: BeautifulSoup, requests, pandas.
2. **Process**: 
   - Scraped data from SEBI website for June 2024.
   - Extracted 112 columns of data for each of the 512 portfolio managers.
   - Stored the scraped data in an Excel file.

### Data Organization in Excel
1. **Formatting**: Organized the raw data into a structured format.
2. **Sheet Creation**: Created additional sheets to process and analyze the data.
3. **VLOOKUP and Calculations**: Used VLOOKUP to extract specific data points and performed various calculations on the data.

## Results
The project successfully scraped and organized data for 512 portfolio managers. The data includes comprehensive details about each portfolio manager's performance metrics and other relevant information.

## Conclusion
This project demonstrates the use of Python for web scraping and Excel for data organization and analysis. The scraped data provides valuable insights into the performance of portfolio managers as of June 2024.

## Future Work
- Automate the scraping process to update the data periodically.
- Implement additional data analysis and visualization techniques in Excel or Python.

