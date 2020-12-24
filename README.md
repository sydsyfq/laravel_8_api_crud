My name is Syed Syafiq bin Syed Alias<br />
Email address: syedsyafiq12@gmail.com<br />

This is a REST API for the user model. This API can get all & single user, create, edit and delete (CRUD).<br />
The API only can be accessed if the user is authenticated through Laravel passport.<br />

1. To test this API, kindly use the Postman application.<br />
2. To register or create a user, use POST and insert http://localhost:8000/api/register and insert name, email, and password in the body.<br />
3. To login, use POST and insert http://localhost:8000/api/login insert email and password in the body.<br />
4. To get all user, use GET and insert http://localhost:8000/api/users.<br />
5. To get one user by inserting their ID, use GET and insert http://localhost:8000/api/users/{id}.<br />
6. To edit user, use PATCH and insert http://localhost:8000/api/users/{id} and insert the intended data to be edit in the body.<br />
7. To delete a user, use DELETE and insert http://localhost:8000/api/users/{id}.<br />
8. To paginate the GET request, use GET and insert http://localhost:8000/api/paginate.<br />
9. For filtering, I am sorry, but I didn't manage to make it.<br />
10. To upload txt/csv/excel and download user list into excel, please go to this URL http://localhost:8000/importExportView.
