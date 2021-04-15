# Data Science & Business Analytics Tasks

# TASK 1

Prediction using Supervised ML

(Level - Beginner)

● Predict the percentage of an student based on the no. of study hours.

● This is a simple linear regression task as it involves just 2 variables.

● You can use R, Python, SAS Enterprise Miner or any other tool

● Data can be found at http://bit.ly/w-data

● What will be predicted score if a student studies for 9.25 hrs/ day?


## Importing the required libraries!
```import pandas as pd 
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np 
%matplotlib inline
```

# Graphs 

### Scatter Plot

![image of Scatterplot](https://github.com/samarth3557/Sparks_Foundation_Intern_tasks/blob/main/Task_1/task_1_images/Scatterplot.png)

### Reg plot

![image of Scatterplot](https://github.com/samarth3557/Sparks_Foundation_Intern_tasks/blob/main/Task_1/task_1_images/regplot.png)


### What will be predicted score if a student studies for 9.25 hrs/ day?
``` hours = np.array([9.25]).reshape(-1,1)
pred = reg.predict(hours)
print("No of Hours = {}".format(hours))
print("Predicted Score = {}".format(pred[0]))
```

### Ouput 
```
No of Hours = [[9.25]]
Predicted Score = [93.19193983]
```



