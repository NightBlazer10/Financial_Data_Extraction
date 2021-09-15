# Financial_Data_Extraction

The Financial Data was extracted from moneycontrol.com

## Objective
* Extracting Financial Data from a financial website
* Manipulation of the Extracted Data to make it ready for furthur analysis

## Libraries Used:
* Selenium
* BeautifulSoup
* Requests
* Pandas
* urllib
* Numpy

## Process
### Extracting the Data from the Website 
* Inputing the url of the balance sheet , profit and loss statement and cash flow statement in the repective varialbles
* Using Selenium to Extract the source code of the page
* Parsing the Source code using BeautifulSoup Library
* Using Selenium and Python Slicing to locate and extract the Financial Data tables from the source code
* Using for loops to append the data from the website into a list
* Using numpy to reshape the list in the same format as of the website
* Using Pandas to convert list into a dataframe for furthur analysis

### Data Manupulation and Data Cleaning
* Dropping the First row as it was not uselful for analysis
* Removing "," and "--" from DataFrame to convert the data into numeric type.
* Using pandas to change data type of each column and concatinating numeric columns into a new dataframe

## Value Added
* The process to extract Financial Data of Balance Sheet , Profit and Loss Statement and Cash Flow into a DataFrame with appropriate DataType is automated.
