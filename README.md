# stocks-analysis

# Overview of Project: Explain the purpose of this analysis.
The purpose fo ths analysis to have a deep understanding of the returns for 11 stocks in 2018 and the effect of run time for the refactor code.

# Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
<img src="https://github.com/shawnkitagawa/stocks-analysis/blob/main/data%20stocks%201.png"/>   (All Stocks 2018)
-----------------------------------------------------------
<img src="https://github.com/shawnkitagawa/stocks-analysis/blob/main/data%202.png" />    (All Stocks 2017)

When looking at the tables of 2018 and 2017 of 11 selected stocks, it clearly shows that 2017 has overall high return compare to 2018.



<img src="https://github.com/shawnkitagawa/stocks-analysis/blob/main/nested%20for%20loop.png"/>   (original script)
-------------------------------------------------------------------------------------
<img src="https://github.com/shawnkitagawa/stocks-analysis/blob/main/two%20for%20loops.png"/>   (refactored script)

The execution time are totally different when comparing the original script and the refactored script. The original version had an average of 0.9 seconds of run time. On the other hand, the refactor version had an average of 0.18 seconds of runtime. This tells that the refactor version is about 5 times faster than the original script. It is because the refactor script use efficient logic. The original script uses a nested for loop to gather data but the refactored script uses two loops to gather data and also an index value to direct in each list. 

# Summary: In a summary statement, address the following questions.

# What are the advantages or disadvantages of refactoring code?
The advantage of refactoring code is that the run time is much more faster because the logic is more efficient. The negative side is that it is time consuming to refactoring the code. 

# How do these pros and cons apply to refactoring the original VBA script?
The bigger the data is, the more efficient the refactoring code is, which could save a lot of time. On the other hand, since it is time consuming to refactor the code, if the data is small and the run time does not have much difference, it might be better to leave the original script.