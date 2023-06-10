# Django

## What are the key components of the Django framework, and how do they contribute to building a web application?
### URLs and views
### Templates
### Forms
### Object-relational mapper
### Authentication

## What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?
### Tailwind CSS is a utility-first CSS framework designed to streamline web development. Its purpose is to provide a comprehensive set of small, atomic utility classes that can be directly applied in HTML markup, allowing developers to style elements efficiently without writing custom CSS. With Tailwind CSS, developers can rapidly prototype and build custom designs by combining and configuring these utility classes. 

### Bootstrap CSS is a comprehensive CSS framework that offers a pre-built set of components, styles, and layout options. It follows a component-centric approach, providing ready-to-use classes and components for consistent and responsive designs. Unlike Tailwind CSS, Bootstrap CSS offers a more opinionated design system with a collection of pre-defined components, making it easier to create consistent designs and prototypes.


## During a typical web request-response cycle, Django's MVT architecture functions as follows:

### The user sends a request by accessing a specific URL.
### Django's URL dispatcher maps the URL to the corresponding view function or class.
### The view function or class receives the request, interacts with models to retrieve or manipulate data, and prepares the necessary data for rendering.
### The view passes the data to the template, which generates HTML using the template logic and the received data.
### The generated HTML response is sent back to the user's browser for display.