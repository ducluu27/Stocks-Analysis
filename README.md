# Kickstarter Challenge #2
## Overview of Project
### Purpose
The purpose of this project is to provide Steve with with stock information over the last few years. The information provided includes the ticker, total daily volume and the percent return of the stock in 2017 and 2018. By refactoring the Module 2 solution code the information will be able to switch back from 2017 and 2018. By doing do, this will provide Steve with access to the stock returns quickly and efficiently from a specific year.
### Results
#### 2017
Based on the results of the 2017 stock refactor, all stocks but TERP showed a positive return. TERP had a -7.2% in returrn while the stock with the highest return percentage is DQ at 199.4%. The refactor code for 2017 took about 0.16 seconds to run. When comparing the run time to the non refactor code, the refactor code ran a lot quicker.

![2017](https://github.com/ducluu27/Stocks-Analysis/blob/master/Resources/All%20Stock%202017.png)


![2017](https://github.com/ducluu27/Stocks-Analysis/blob/master/Resources/2017%20run%20time.png)

#### 2018
Based on the results of the 2018 stock refactor, all the stocks showed a decrease in returns except for ENPH and RUN. RUN had the highest return at 85%, while the stock with the biggest lost in is DQ at 62.6%. The refactor code for 2018 toook about .16 to run. Just like the 2017 refactor code, the 2018 refactor code also ran faster than the nonrefactor code. 

![2018](https://github.com/ducluu27/Stocks-Analysis/blob/master/Resources/All%20Stock%202018.png)


![2018](https://github.com/ducluu27/Stocks-Analysis/blob/master/Resources/2018%20run%20time.png)
### Summary
There are many benefits to running a refactored code than a non refactor code. The first reason is that the results are pulled faster as shown in the project. Also, refactor codes keep the codes from repeating themselves. They are also a lot cleaner to read and make edits. One of the disadvantages of running a refactor code is that if more data is needed to be added, the entire code would need to be updated. Another downside is that there are a lot of variables that are need to be used and it can be very easy to lose track of variables. When comparing the advantages of a original and refactored VBA script, one advantage would be that the refactored script processes quicker than the original. Refactored scripts are a lot cleaner and easier to read than the orignal. But the original is easier to add information to than the refactored scripts. 
