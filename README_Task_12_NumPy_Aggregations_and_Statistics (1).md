# Task 12 - NumPy Aggregations and Statistics

## Name

Jasmitha

## Internship

Veda Technology - Data Science Track

## Objective

Learn NumPy aggregation and statistical functions.

## Tools

-   Python
-   NumPy
-   Jupyter Notebook / VS Code

``` python
import numpy as np

marks = np.array([85,90,78,92,88,76,95])

print("Dataset:", marks)
print("Sum =", np.sum(marks))
print("Mean =", np.mean(marks))
print("Median =", np.median(marks))
print("Minimum =", np.min(marks))
print("Maximum =", np.max(marks))
print("Standard Deviation =", np.std(marks))
print("Variance =", np.var(marks))
```

### Output

    Dataset: [85 90 78 92 88 76 95]
    Sum = 604
    Mean = 86.28571428571429
    Median = 88
    Minimum = 76
    Maximum = 95
    Standard Deviation = 6.36
    Variance = 40.53

## 2D Array Example

``` python
import numpy as np

data = np.array([
    [10,20,30],
    [40,50,60],
    [70,80,90]
])

print(np.sum(data, axis=0))
print(np.sum(data, axis=1))
print(np.mean(data, axis=0))
```

### Output

    axis=0 : [120 150 180]
    axis=1 : [ 60 150 240]
    Mean   : [40. 50. 60.]

## Aggregation Functions

1.  np.sum()
2.  np.mean()
3.  np.median()
4.  np.min()
5.  np.max()
6.  np.std()
7.  np.var()

## Conclusion

This task demonstrates how to use NumPy aggregation functions to perform
basic statistical analysis on numerical datasets.
