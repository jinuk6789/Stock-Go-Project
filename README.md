# Stock-Go-Project

This project is dedicated for Go Language. The user retrieves stock information from Yahoo Finance API and then creates his own API using Go language.

The user manipulates the retrieved information and creates a local host server to show the data. 

## Specifications

 1. Use the Yahoo Finance API, (https://query1.finance.yahoo.com/v10/finance/quoteSummary/(?)?modules=summaryDetail%2CsummaryProfile) - Change the stock symbol to the user-desired company stock symbol at where (?) is located within the URL.
 
 2. Five information that are included in type Stock struct in Go Lang are Name, Symbol, Price, Capacity, and Location of the company.
 
 3. Because there isn't an information about the requested company's name and symbol, the user has to hard code the information for Name and Symbol manually. - This will be fixed as soon as possible.
