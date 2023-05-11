# EmployeeAddressProject 
### This project is a Employee address project built using Spring Boot with java.
## Framework Used
* Spring Boot
## Language Used
* Java
## Data Model
The Employee Class And Address Class is defined inside the model packages which has the following attributes:

## Address Class:-

id; : Address ID
street : Address street
city : Address city
state : Address state
zipcode : Address zipcode

## Employee Class:-

id : Employee Id
firstName : Employee firstName
lastName : Employee lastName
address : Object of Address


## Functions used :-
API Endpoints :-

### addEmployees
PostMapping: /addEmployees
* This endpoint makes a call to method in EmployeeService class which is connected to database. In database we add a new Employee given through API.

GetMapping:
* This endpoint returns data of specific Employee based on id through API.

PutMapping:
* This endpoint makes a call to method in EmployeeService class which is connected to database. In database we update Employee.

DeleteMapping:
* This endpoint makes a call to method in EmployeeService class which is connected to database. In database we delete Employee through API.

### addAddress

PostMapping:
* This endpoint makes a call to method in AddressService class which is connected to database. In database we add a new Address given through API.

GetMapping:
* This endpoint returns Address.

PutMapping:
* This endpoint makes a call to method in AddressService class which is connected to database. In database we update Address.

DeleteMapping:
* This endpoint makes a call to method in AddressService class which is connected to database. In database we delete Address through API.

## Project Summary
I have created Employee Address project. In this project I have used @OneToOne maping and the user can add the Employee & Address. Can delete, update. can find. etc...