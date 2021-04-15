# Topic : Data Science & Business Analytics Tasks

## TASK 2

Prediction using Unsupervised ML
(Level - Beginner)

● From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually. 

● Use R or Python or perform this task

● Dataset : https://bit.ly/3kXTdox

● Sample Solution : https://bit.ly/3cGyP8j

## Importing the Required Libraries!
```
import pandas as pd 
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np 
%matplotlib inline 
```

# Graphs :

## Joint plot

![image of jointplot](https://github.com/samarth3557/Sparks_Foundation_Intern_tasks/blob/main/Task_2/Task_2_images/jointplot.png)

## Pair plot

![image of pairplot](https://github.com/samarth3557/Sparks_Foundation_Intern_tasks/blob/main/Task_2/Task_2_images/pairplot.png)


## Chosing k = 3 

```
kmeans = KMeans(n_clusters = 3, init = 'k-means++', max_iter = 300, n_init = 10, random_state = 0)
y_kmeans = kmeans.fit_predict(x)
```
## Scatter  plot

![image of scatterplot](https://github.com/samarth3557/Sparks_Foundation_Intern_tasks/blob/main/Task_2/Task_2_images/scatter.png)


