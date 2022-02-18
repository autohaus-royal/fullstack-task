# Autohaus Royal Fullstack Task

Create a application that makes it possible to manage customer data. 

## General Information

- This repository is only used to provide the task
- For implemenmentation use a repository in your own GitHub account
- Make sure the respository used is public
- After completion submit a link with the repository that contains the solution
- Make sure to show proper Git usage 

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

The backend is implemented as a RESTful webservice which implements the 4 CRUD operations.

-	The backend has to be implemented in node.js using express.
-	For persistent storage use  mongoDB 
-	Provide a clean appropriate architecture, pay attention to segregation of duties 
- The backend provides the following endpoints
  -  GET /customer/:id	
  -  GET /customer?lastname=Schmidt
  -  POST /customer
  -  DELETE /customer/:id

## Frontend Part

The frontend is implemented with React and requires the following components:

- Add a new customer
- Search for a customer
- List with search result
- Delete a customer
