# biased-coin

This code generates a mystery coin with an unknown bias and essentially compares it with another known fair coin to decide if the bias exists or not.

#### Example output when fair:

Probability of mystery coin flipping heads:  0.5  
Observed proportion of heads:  0.5056666666666667  
Sample mean:  15.17  
Control mean:  15.068  
p-value:  0.236660952588  
The p-value is greater than  0.01 , therefore we can say with  99 % confidence that our mystery coin is fair.  

#### Example output when biased:

Probability of mystery coin flipping heads:  0.4936555647123755  
Observed proportion of heads:  0.49329999999999996  
Sample mean:  14.799  
Control mean:  15.118  
p-value:  0.000259936016099  
The p-value is less than  0.01 , therefore we can say with  99 % confidence that our mystery coin is unfair.  

Written in Python 3.5, using Jupyter.

##### Reference Materials:

https://repl.it/examples

https://www.continuum.io/documentation

https://www.scipy.org/getting-started.html

https://docs.python.org/3/tutorial/controlflow.html

http://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html

https://www.daniweb.com/programming/software-development/threads/183540/coin-flip-python-newbie-

http://www.tutorialspoint.com/python/python_nested_loops.htm

http://hamelg.blogspot.ca/2015/11/python-for-data-analysis-part-24.html

http://stackoverflow.com/questions/477237/how-do-i-simulate-flip-of-biased-coin-in-python

http://stackoverflow.com/questions/5012560/how-to-query-seed-used-by-random-random

http://iaingallagher.tumblr.com/post/50980987285/t-tests-in-python

http://stackoverflow.com/questions/10897339/python-fetch-first-10-results-from-a-list


