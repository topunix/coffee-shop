# Coffee Shop Full Stack

![coffee-shop](https://user-images.githubusercontent.com/833824/82158436-d0be5c80-9855-11ea-9122-8ec4d8436aa5.jpg)

### Introduction

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. 

The full stack drink menu application must:

1) Display graphics representing the ratios of ingredients in each drink.
2) Allow public users to view drink names and graphics.
3) Allow the shop baristas to see the recipe information.
4) Allow the shop managers to create new drinks and edit existing drinks.


## About the Stack

### Backend

The `./backend` directory contains a SQLAlchemy module and a Flask server with the required endpoints and Auth0 integration for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. The environment variables found within (./frontend/src/environment/environment.ts) is for the Auth0 configuration. 

[View the README.md within ./frontend for more details.](./frontend/README.md)
