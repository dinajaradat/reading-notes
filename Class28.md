## Django CRUD and Forms

## How do Django Forms facilitate user input handling, and what are some key components of creating a form using the Django framework?
###  They provide a convenient way to define, validate, and process user-submitted data. By utilizing Django Forms, you can streamline the process of building HTML forms, handling form submission, and performing data validation.

## The components form the foundation for creating and handling forms in Django:
### Form class
### Fields
### Rendering
### Validation
### Submission handling
### Error display
### CSRF protection

## Describe the function of Django Views in handling HTTP requests, and outline the differences between function-based views and class-based views.

## Function-based views:

### Function-based views are defined as Python functions.
### They receive a request object as an argument and return an HTTP response.
### Function-based views provide a simple and straightforward way to handle requests and responses.
### They are ideal for small and straightforward views that don't require extensive reusable behavior.
### URL routing directly maps URLs to function-based views.

## Class-based views:

### Class-based views are defined as Python classes.
### They inherit from Django's View or other predefined class-based views.
### Class-based views provide a more object-oriented approach to handling requests.
### They offer a range of built-in methods (e.g., get(), post()) for handling different HTTP methods.
### Class-based views promote code reusability through mixins and inheritance.
### They support mixins for adding common functionality to views, such as authentication, permission checks, etc.
### Class-based views often provide a more structured and organized way to handle complex views with multiple actions.
### URL routing maps URLs to class-based views using the as_view() method.