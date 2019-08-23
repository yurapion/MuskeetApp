# MuskeetApp
*Some Data such as Users, CarWorkShops and Appointments will be created and stored automatically*
*Username and email are unique*

Postman:
USERS:

GET request => http://localhost:5000/api/users/ Get all users

GET request => http://localhost:5000/api/users/1 Get concrete user

POST request => http://localhost:5000/api/users/register/ Create a new user

PUT request => http://localhost:5000/api/users/1 Modify a concrete User

DELETE request => http://localhost:5000/api/users/1 Delete a concrete User

CarWorkKShops:

GET request => http://localhost:5000/api/carworkshop/ Get all car workshops

GET request => http://localhost:5000/api/carworkshop/1 Get a concrete car workshop

!! GET request => http://localhost:5000/api/carworkshop/GetCarWorkShops/2 Get All car workshops with math concrete user's city !! 

POST request => http://localhost:5000/api/carworkshop/register Create a new car workshop

PUT request => http://localhost:5000/api/carworkshop/1 Modify a concrete car workshop

DELETE request =>http://localhost:5000/api/carworkshop/1 Delete a concrete car workshop

Appointment:

GET request => http://localhost:5000/api/appointment/ Get all apointments

POST request => http://localhost:5000/api/appointment/ Create a new appointment

PUT request => http://localhost:5000/api/appointment/3 Modify concrete appointment

DELETE request => http://localhost:5000/api/appointment/3 Delete concrete appointment
