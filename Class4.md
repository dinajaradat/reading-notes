## What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?
### Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.
### classes provide a blueprint for creating objects
### objects are the actual instances created from the blueprint.
    class NumberHolder:

    def __init__(self, number):
       self.number = number

    def returnNumber(self):
       return self.number

    var = NumberHolder(7)
    print(var.returnNumber())


## Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python
### technique where a function will continue to call itself and repeat its behavior until some condition is met to return a result
    #n! = n x (n−1) x (n−2) x (n−3) ⋅⋅⋅⋅ x 3 x 2 x 1

    def factorial_recursive(n):
        if n == 1:
            return 1
        else:
            return n * factorial_recursive(n-1)

### structure made up of two parts: base case and recursive case
### base case:specifies the condition under which the recursion will stop. Without a base case, the function will keep calling itself infinitely
### recursive case:specifies the condition under which the function calls itself recursively, and it should bring the problem closer to the base case

## What is the purpose of pytest fixtures and code coverage in testing Python code?
### Pytest fixtures: functions that you define to set up a specific test scenario or environment
### Code coverage: to measure how much of your code is being tested

## Explain how they can be used together to improve the quality and maintainability of a project
###  improve the quality and maintainability of the Python project.Pytest fixtures help reduce duplication and improve readability.Code coverage identify areas of  code that are not being tested

