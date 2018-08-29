# Flask REST API

## Description
This project is implemented with Python using Flask, and is a secure REST API designed for the retail sector.

The API enables stakeholders to efficiently store multiple items to a database, where the items are allocated to a specified store branch.

## Implementation
Users can use the API endpoints to register and login, to post, update, get or delete items and stores.

Each item requires a name, price and its associated store id to be successfully posted/updated to the database.
Stores can be posted, updated and deleted from the database, but require a name to be saved. It is possible to retrieve all the stores in the database and their associated items.

Please also note, obtaining access to stores and items requires users to be logged in with JWT tokens.



## Installation

```
pip install Flask
pip install Flask-RESTful
pip install Flask-JWT
pip install Flask-SQLAlchemy

python app.py
```
