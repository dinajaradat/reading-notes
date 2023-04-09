## What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?
### When opening a file in Python using the with statement, the file object is automatically closed after the block of code inside the with statement is executed. This ensures that the file is properly closed and any resources associated with it are released, even in cases of error.

## the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method
### read() reads the entire contents of the file at once, while readline() reads one line at a time

### with open('dog_breeds.txt', 'r') as reader:
    # Read & print the entire file
     print(reader.read())       



### with open('dog_breeds.txt', 'r') as reader:
     # Read & print the first 5 line 
     print(reader.readline()) 
     print(reader.readline())
     print(reader.readline())
     print(reader.readline())
     print(reader.readline())


## describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example

### Exception handling is a technique used to  handle errors and unexpected events that occur during the execution of a program

    try:
       file = open("example.txt", "r")
       content = file.read()
       print(content)
    except FileNotFoundError:
       print("File not found!")
    else:
       print("File read successfully!")
    finally:
       file.close()
       print("File closed!")

### - try to open a file named "example.txt" and read its contents using the read()
### If the file is not found, a FileNotFoundError is raised, and the - program prints an error message.
### - If the file is successfully read, the program prints "File read successfully!"
### - everything in the finally clause will be executed. It does not matter if you encounter an exception somewhere in the try or else clauses
