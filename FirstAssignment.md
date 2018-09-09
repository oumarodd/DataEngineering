
### Rodda Ouma
### Data Engineering and Mining 
#### Assignment 1


In this assignment ,  we will write a simple program to generate a scatter plot of a linear function using matplotlib.

First, we import the required packages as seen below


```
%matplotlib inline

import matplotlib
import numpy as np
import matplotlib.pyplot as plt

```


```
We then create dummy vectors to hold the values
```


```
x=[4,5,6,8,9,10,11]
```


```
y=[1,2,5,7,8,3,4]
```

We lastly introduce the scatter plot funciton.


```
plt.scatter(x,y,label= 'skitscat', color='k', s=25, marker ="o")
```




    <matplotlib.collections.PathCollection at 0x1bc734c1da0>




![png](output_7_1.png)

