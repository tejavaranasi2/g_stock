# g_stock
this project uses lstm architecture to predict expected price form prices of past 50 days .
it is developed with so that unnecessary memory wont be a problem
   ### it is observed that training lstm with > 200 steps casues vanishing gradient problem
error calculation is done in a very unique way.

many data sets consisting of time_steps number of elements are trained seperately and error is calculated . this is done for almost 1000 data sets to find 
coefficient of variance (1%)

## Network architecture and parameters:
