##  variable scope
### the region of a program where a variable is defined and can be accessed. In Python, there are two types of variable scopes: global and local.

## the difference between local and global scope
### Global scope: The names that you define in this scope are available to all your code.

      var = 100
      def func():
        return var  # You can access var from inside func()
 
      func()
      100
      # var  # Remains unchanged
      100
### Local scope: The names that you define in this scope are only available or visible to the code within the scope.
      def square(base):
        result = base ** 2
        print(f'The square of {base} is: {result}')
  
      square(10)

      # The square of 10 is: 100
      # result  # Isn't accessible from outside square()


## How do the global and nonlocal keywords work in Python

### The statement define a list of names that are going to be treated as global names, it can be accessed and modified from anywhere in the program

### The nonlocal statement  is used inside a nested function to declare that a variable is not local to the nested function, but rather is a variable from the enclosing function. 