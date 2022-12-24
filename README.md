# Stock-Analysis
## Overview
The purpose of this workbook is to analize stock shares for 2017 and 2018. There is particular attention paid to one stock (DQ) and a follow up analysis on all stocks in the data set. 
## Results

Looking at all of the stocks between 2017 and 2018, there was a sharp downhill return in 2018. 2017 Showed large returns for all but one stock analyzed while 2018 had negative returns for all but 2 stocks. See screen shots below.

![VBA_Challenge_Results_2017](https://github.com/MichaylaGilchrist/Stock-Analysis/blob/main/VBA_Challenge_Results_2017.PNG)
![VBA_Challenge_Results_2018](https://github.com/MichaylaGilchrist/Stock-Analysis/blob/main/VBA_Challenge_Results_2018.PNG)

Prior to refractoring the code to increase the time that it took to return the stock analysis the average time was 3.15 seconds and post refractoring was 0.078 seconds. The code refractoring gave an average savings of 3.076 seconds. 
The execution times for these returns after the script refractoring are as follows: 0.07910156 for 2017 and 0.078125 seconds for 2018.

![VBA_Challenge_2017](https://github.com/MichaylaGilchrist/Stock-Analysis/blob/main/VBA_Challenge_2017.PNG)
![VBA_Challenge_2018](https://github.com/MichaylaGilchrist/Stock-Analysis/blob/main/VBA_Challenge_2018.PNG)

The execution times for these returns before the script refractoring are as follows: 2.729004 for 2017 and 3.580078 seconds for 2018. 

![green_stocks_2017](https://github.com/MichaylaGilchrist/Stock-Analysis/blob/main/green_stocks_2017.PNG)
![green_stocks_2018](https://github.com/MichaylaGilchrist/Stock-Analysis/blob/main/green_stocks_2018.PNG)

## Summary

Refractoring code comes with some challanges. An advantage to working with existing code is that you have proven the  code to work. A disadvantage is that when incorporating new code there is the opportunity to cause errors or need to change the code that was working previously. The goal of refractoring is to create better code but you'll potentially make it worse before it gets better. 

These same issues applied when refractoring the orginal VBA script. Although the amount of code increased and my original number of errors increased it did return a faster result than with the previous edits.  
