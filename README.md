# Simple Stock Management

This a simple stock management and inventory application. 

The app is designed to allow "stores" to request transfers of stock (or "order" it) from a central stock database (the "warehouse"). Warehouse stock is adjusted as stock transfers are ordered.

It has web frontend that connects to a RESTful API backend. Data is stored in either a SQLite or mySQL database.

## Key features

- Administrator may add, edit and delete stock from database.
- Store managers may request transfers ("order") stock from the "warehouse".
- Warehouse stock levels are adjusted in accordance with incoming transfers ("orders").
- Email notifications are dispatched to the administrator(s) and store manager(s).
- Dynamic search of stock lines (SKU and description).
- Configurable pagination of results table.

## Key technologies

- Python 3.6
- Django
- Django-rest-framework
- Javascript (ReactJS)
- HTML5
- CSS3

## Live Demo

There is a live demo available here:

https://stockmanagement.staging.aninstance.com

There are two test users - one for the warehouse administrator, the other for a 'store manager'. Credentials are:

Adminstrator:
Username: test_admin
Password: jduejHje(89K

Manager:
Username: test_manager
Password: jduejHje(89K

## Development Roadmap

- Addition of independent databases for each "store". 

## Authors
- Dan Bright (Aninstance Consultancy), productions@aninstance.com