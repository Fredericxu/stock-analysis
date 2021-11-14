# stock-analysis
VBA Challlenge
## Overview of Project: Explain the purpose of this analysis.
The purpose of this analysis is to analyze the price change and accumulative volume in year 2017 and 2018 for 12 selected stocks.
## Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
### performance of the stock
Click [here](https://github.com/Fredericxu/stock-analysis) for pictures VBA_Challenge_2017 and VBA_Challenge_2018.
As to be shown in the picture, most stocks have better performance in year 2017 than in 2018. TERP is the only stock with negative return in year 2017. ENPH and RUN are the only 2 positive return stocks in year 2018. 
### execution times of the scripts
Click [here](https://github.com/Fredericxu/stock-analysis/tree/main/Resources) to reach the pictures for execution time of original scripts.
The original scripts with execution times for 2.5-5 seconds and the refactored scripts are much faster with the execution time about 0.1 second.
## Summary: In a summary statement, address the following questions.
### What are the advantages or disadvantages of refactoring code?
Refactoring code has advantage for execution time to be much less than the original code as well as the number of loops was reduced from 2 to 1. 
The disadvantage is this code is only rely on the pre-sorting of column A and if the ticker content is random in column A it would not work at all.
### How do these pros and cons apply to refactoring the original VBA script?
Cutting off as much as I can for the number of loops would be significant to help reduce the execution time for the original scripts.
The refactoring coding relies on the change of content in Column A to return the +1 value to add to the tickerindex.
The cons still apply to all scripts as it relies on the pre-sorting of the column A content. 

