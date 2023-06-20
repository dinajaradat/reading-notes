## The key benefits of using a Django Custom User Model are flexibility, scalability, improved authentication, integration capabilities, and extensibility.

## The default user model in Django uses a username to uniquely identify a user during authentication. If you'd rather use an email address, you'll need to create a custom user model by either subclassing AbstractUser or AbstractBaseUser.

## Options:

### AbstractUser: Use this option if you are happy with the existing fields on the user model and just want to remove the username field.
### AbstractBaseUser: Use this option if you want to start from scratch by creating your own, completely new user model.


## The process of creating and implementing a Custom User Model in Django, including the necessary changes to settings.py and the required model fields

## Setup

### To start, create a new Django project from the command line. We need to do several things:

### create and navigate into a dedicated directory called accounts for our code
### install Django
### make a new Django project called config
### make a new app accounts
### start the local web server

## AbstractUser vs AbstractBaseUser
### There are two modern ways to create a custom user model in Django: AbstractUser and AbstractBaseUser. In both cases we can subclass them to extend existing functionality however AbstractBaseUser requires much, much more work.

## Custom User Model
### Creating our initial custom user model requires four steps:

### update config/settings.py
### create a new CustomUser model
### create new UserCreation and UserChangeForm
### update the admin