My name is Syed Syafiq bin Syed Alias
Email address: syedsyafiq12@gmail.com

This is a REST API for the user model. This API can get all & single user, create, edit and delete (CRUD),
The API only can be accessed if the user is authenticated through Laravel passport.

To test this API, kindly use the Postman application.<br />
To register or create a user, use POST and insert http://localhost:8000/api/register and insert name, email, and password in the body<br />.
To login, use POST and insert http://localhost:8000/api/login insert email and password in the body.<br />
To get all user, use GET and insert http://localhost:8000/api/users.<br />
To get one user by inserting their ID, use GET and insert http://localhost:8000/api/users/{id}.<br />
To edit user, use PATCH and insert http://localhost:8000/api/users/{id} and insert the intended data to be edit in the body.<br />
To delete a user, use DELETE and insert http://localhost:8000/api/users/{id}.<br />
To paginate the GET request, use GET and insert http://localhost:8000/api/paginate.<br />
For filtering, I am sorry, but I didn't manage to make it.
