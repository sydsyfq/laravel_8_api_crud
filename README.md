My name is Syed Syafiq bin Syed Alias
Email address: syedsyafiq12@gmail.com

This is a REST API for the user model. This API can get all & single user, create, edit and delete (CRUD),
The API only can be accessed if the user is authenticated through Laravel passport.

To test this API, kindly use the Postman application.
To register or create a user, use POST and insert http://localhost:8000/api/register and insert name, email, and password in the body.
To login, use POST and insert http://localhost:8000/api/login insert email and password in the body.
To get all user, use GET and insert http://localhost:8000/api/users.
To get one user by inserting their ID, use GET and insert http://localhost:8000/api/users/{id}.
To edit user, use PATCH and insert http://localhost:8000/api/users/{id} and insert the intended data to be edit in the body.
To delete a user, use DELETE and insert http://localhost:8000/api/users/{id}.
To paginate the GET request, use GET and insert http://localhost:8000/api/paginate.
For filtering, I am sorry, but I didn't manage to make it.
