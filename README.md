# Autohaus Royal Fullstack Task

Create a application that makes it possible to manage customer data. 

## Requested Features

- Customer data includes
  - Last name
  -	First name
  -	Gender
  -	Street
  -	Postal code
  -	City
- Create customer:    All above data fields are mandatory
- Search customers:  For sake of simplicity only search last names
- Edit customer:         All data fields must be changeable
- Delete customers

The application consists of a backend part and a frontend part. We recommend to implement both parts separately.

## Backend Part

The backend has to be implemented as a RESTful webservice which implements the 4 CRUD operations.

•	The backend has to be implemented in node.js using express.
•	For persistent storage use  mongoDB 
•	The backend provides the following routes
o	GET /customer/:id
o	GET /customer?lastname=Schmidt
o	POST /customer
o	DELETE /customer/:id
•	Provide a clean appropriate architecture, pay attention to segregation of duties using layered architecture.

Frontend Part

The frontend is to be implemented with React and requires the following components:

•	Add a new customer
•	Search for a customer
•	List with result of search
•	Delet a customer
