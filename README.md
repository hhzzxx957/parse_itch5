# A python parser for Nasdaq ITCH protocol (version 5.0) 

## What?
This is a simple program to parse the ITCH 5.0 file, the example file is from ftp://emi.nasdaq.com/ITCH/Nasdaq_ITCH/01302019.NASDAQ_ITCH50.gz  
The main purpose of this program is to get volume-weighted average price (VWAP) for each stock, but can be extended to other uses.

## How?
This program is wirtten in python 3.6.8 in jupyter notebook  
with following packages : pandas, datetime, struct, time

Code is presented in jupyter notebook in src folder  
Place the dataset into data folder.  
Change the file address and date of the input file before use.

The data format is defined by http://www.nasdaqtrader.com/content/technicalsupport/specifications/dataproducts/NQTVITCHspecification.pdf



## Disclaimer
The codes and content are purely informative and none of the information provided constitutes any recommendation regarding any security, transaction or investment strategy for any specific person. The implementation described in the notebook could be risky and the market condition could be volatile and differ from the period covered above. All trading strategies and tools are implemented at the users’ own risk.
