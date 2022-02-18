# fullstack-task

Task

Create an application that makes it possible to manage customer data. This application has the following features

•	Customer data includes
o	Last name
o	First name
o	Gender
o	Street
o	Postal code
o	City
•	Create customer:    All above data fields are mandatory
•	Search customers:  For sake of simplicity only search last names
•	Edit customer:         All data fields must be changeable
•	Delete customers

The application itself consists of a backend and a frontend. I recommend to implement both parts separately.

Backend Part

The backend has to be implemented as a RESTful webservice which implements  the 4 CRUD operations.

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
