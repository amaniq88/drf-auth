# Lab: Authentication & Production Server
adding Authentication to the API 
- Add JWT Authentication to your API.
Install needed libraries in project configuration and/or site settings.
- Keep any pre-existing authentication so DRF Browsable API still usable.
Install needed libraries in project configuration and/or site settings.


Steps to do the Testing on postman : 
1- Open the application 
2- on the address par place type the address http://127.0.0.1:8000/api/v1/party-list
3- Select whether to POST or GET 
4- Select  GET 
5- in Authorization tab beside the type select Bearer Token 
6- get the token from the webpage by access the following URL http://127.0.0.1:8000/api/v1/token then enter the Admin username and password .
7- copy the token then paste on the postman Barer .
8- data will be retrived from the API .
9 Same to check the POST but add in the body tab the data which will be posted 
