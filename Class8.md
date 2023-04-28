## The basic syntax of Python list comprehension is
       my_new_list = [ expression for item in list ]
### expression we’d like to carry out. expression inside the square brackets.
### object that the expression will work on. item inside the square brackets.
### iterable list of objects to build our new list from. list inside the square brackets.


## create a list using a for loop
        squares = []

        for x in range(10):
            squares.append(x**2)

        print(squares)

## create a list using list comprehension
        squares = [x**2 for x in range(10)]

        print(squares)
## What is a decorator in Python?
### decorator is a function that takes another function and extends the behavior of the latter function without explicitly modifying it.

## example of a simple decorator function

          def my_decorator(func):
              def wrapper():
                   print("Something is happening before the function is called.")
                   func()
                   print("Something is happening after the function is called.")
              return wrapper

          def say_whee():
               print("Whee!")

          say_whee = my_decorator(say_whee)
          say_whee()


          # Something is happening before the function is called.
          # Whee!
          # Something is happening after the function is called.