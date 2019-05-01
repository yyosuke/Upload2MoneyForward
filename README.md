# Upload2MoneyForward
This program is to register expenses and incomes to MoneyForward by uploading csv files.  

## Description
This program is to regsiter expenses and incomes data to MoneyForward by uploading csv files.

## Features
- regsiter expenses and income data to MoneyForward by uploading csv files 
- You can use some parameter following:  
  -date
  -price(income and expense
  -large-category  
  -middle-category  
  -content  

## Requirement
- Python 3.6.3 or later  
- selenium 3.141 or later  
- ChromeDriver 73.0.3683.103 or later

## Usage
1. You can install selenium using:  
```pip install selenium```  
  
2. You can get ChromeDriver from the followng site:  
http://chromedriver.chromium.org/downloads

3. You need to move ChromeDriver to the same directory as Upload2MoneyForward.

4. You need to modify the source about your account info.
```
user = "input your userid"
password = "input your password"
```

5. Input file format
This program only allow following CSV format:  
```date,large-category,middle-category,content-field,price```  
You can see sample data from "sample.csv"

## Running Tests
You can execute this program using:  
```python uploadCSVtoMF.py sample.csv```

## Author
[yysosuke](https://twitter.com/yyosuke)

## License
[GPL](https://github.com/yyosuke/Upload2MoneyForward/blob/master/LICENSE)
