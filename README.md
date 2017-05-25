# BLS_data_scraper
Python web scraper retrieves labor force data from the Bureau of Labor Statistics (BLS) website. Data are from the Local Area Unemployment Statistics (LAUS) report. For more info on the data, see: https://www.bls.gov/lau/.  

Data are pulled into a pandas' dataframe and output is delivered in an Excel. 

Python: version 2.7
Libraries: BeautifulSoup, pandas, requests 

Link to BLS data: https://www.bls.gov/web/laus/ststdsadata.txt.

Data are: state-level, monthly, and seasonally-adjusted dating back to 1976.

Metrics included: civilian non-institutional population, total labor force, total employed, and total unemployed. 
