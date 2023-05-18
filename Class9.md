## What is the purpose of dunder methods in Python? Provide an example of a commonly used dunder method.
### special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores
### Dunder methods let you emulate the behavior of built-in types. For example, to get the length of a string you can call len('string').

## A commonly used dunder method is
       1- __repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous.

       2- __str__: The “informal” or nicely printable string representation of an object. This is for the enduser.

## Describe the Python statistics module 
### The Python statistics module is a built-in module in Python that provides functions for calculating basic statistical properties of data. It includes functions for calculating measures such as the mean, median, mode, variance, and standard deviation.

       from statistics import median
       data = [20.7, float('NaN'),19.2, 18.3, float('NaN'), 14.4]
       median(data)   # 16.351

