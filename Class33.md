## What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?
### The primary purpose of JSON Web Tokens (JWTs) is to securely transmit information between parties as a compact and self-contained data format. JWTs are commonly used for authentication and authorization in web applications. They allow the server to generate a token that contains user claims or attributes, which can be verified and trusted by the server for subsequent requests. JWTs are portable, stateless, and can be used across different domains or services. In terms of encoding and decoding data, JWTs consist of three parts: the header, the payload, and the signature. The header specifies the algorithm used to generate the signature. The payload contains the claims or attributes of the token, such as user identification or permissions. The signature is created by combining the header, payload, and a secret key known only to the server. When the server receives a JWT, it can validate the signature using the secret key to ensure the token hasn’t been tampered with. The payload data can then be extracted and used for authorization or other purposes.

## The key components involved in JWT authentication with DRF include:

### Authentication Backend: Provided by the JWT library, this class validates and decodes JWTs, ensuring token validity and extracting user information.
### Token Generation: When a user successfully authenticates, a JWT is generated and returned as a response, typically with an expiration time.
### Token Refresh: Clients can request a new token with a refresh token if the current token expires. This process extends the authentication session without requiring re-login.
### Token Authentication: The authentication backend is added to DRF authentication settings, enabling the framework to authenticate requests using JWTs at the global or per-view level.

## How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

### Install the djangorestframework-simplejwt library.
### Configure the authentication settings in Django's settings.py file.
### Define custom views for token-based authentication, including token creation and token refresh.
### Include the authentication classes and permissions in the desired views or viewsets.
### Use the generated JWTs to authenticate requests by including the token in the request headers or query parameters.


## Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

### Django's built-in runserver is not suitable for production environments because it is not designed for high-traffic or high-performance applications. It is a single-threaded server, which means that it can only handle one request at a time. This can lead to performance bottlenecks and timeouts if your application receives a lot of traffic.

# server options that should be considered for deploying a Django application include:
### Gunicorn
### Nginx
### Apache