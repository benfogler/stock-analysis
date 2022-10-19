# VBA_CHALLENGE

## Overview of Project
This project included stock data from 2017 and 2018, and we used VBA in order to analyze the data set by Ticker and Year.

### Purpose
The purpose of this project was to help Steve identify the best stocks for his parents to invest in based on market trends from 2017 and 2018 by utilizing VBA to create buttons for him to easily sort through the data and determine the best stocks.

## Analysis and Challenges
The analysis consisted of collating the data into 3 distinct columns; Ticker, Total Daily Volume and Return. A selection was created when pressing the button that allowed the macro to run a specific year and realize what was in each column.
The challenges faced for the refactoring were incorporating the ticker volumes to index the tickers.

### Analysis of Outcomes Based on Year 
2017 showed to be a better year across all stocks when compared to 2018. All 2018 stocks showed negative returns except for 2, where as 2017 all stocks were either 0% or positive except for 1.

### Analysis of Outcomes Based on Ticker
RUN and ENPH maintained a positive return both 2017 and 2018, their total daily volume increased significantly from 2017 to 2018 while other were mostly flat.

### Challenges and Difficulties Encountered
The most difficult aspect would have been adjusting the query to pull in all stock data. This was due to the tickerVolume logic that had to be implemented in order to pull them all in.

## Results

- What are two conclusions you can draw about the Outcomes based on Year?
There was a significant market drop in 2018, and not a significant amount of fluctuation in total daily volume in most stocks between the 2 years.

- What can you conclude about the Outcomes based on Ticker?
RUN and ENPH faired the best out of all stocks during the downturn in 2018.

- What are some limitations of this dataset?
It only runs for 2 years and does not show a great overall trend for the stocks over several years. 

- What are some other possible tables and/or graphs that we could create?
Possibly showing a line graph for each day in the respective month might show a clearer picture of flucuations. This could benefit the investors to know whether they could expect sharp drops or rises.
