# Full Stack Coffee Shop 

![coffee-shop](https://user-images.githubusercontent.com/833824/82158436-d0be5c80-9855-11ea-9122-8ec4d8436aa5.jpg)

## Introduction

**Udacafe** is a modern, digitally enabled cafe designed for students to order drinks, socialize, and study effectively.  

This drink menu application offers the following features:  

1. **Visual Ingredient Display**: Graphics showcase the ingredient ratios of each drink, providing a clear visual representation.  
2. **Public Access**: Guests can view drink names and their corresponding graphics without needing special permissions.  
3. **Barista View**: Baristas have access to detailed drink recipes to ensure consistent preparation.  
4. **Manager Controls**: Managers can create new drinks and edit existing ones, allowing flexibility in menu management. 

## About the Stack

### Backend

The `./backend` directory contains a SQLAlchemy module and a Flask server with the required endpoints and Auth0 integration for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. The environment variables found within (./frontend/src/environment/environment.ts) is for the Auth0 configuration. 

[View the README.md within ./frontend for more details.](./frontend/README.md)
