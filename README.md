# Login-API-with-MongoDB----Node.js

RESTFul API for Developing login for any application

NPM Libraries used are:
bcrypt: ^5.0.0
express: ^4.16.4
jsonwebtoken: ^8.5.1
mongodb: ^3.6.3
mongoose: ^5.10.15
multer: ^1.4.2
sharp: ^0.26.3
validator: ^13.1.17


EndPoints:

For Local Enviroment on port 3000
base url: localhost:3000
Create User Accout -> POST: /users/create
User login -> POST: localhost:3000/users/login
User Logout -> POST: /users/logout
Logout all users -> POST: /users/logoutAll
Get user details -> GET: /user/me
Get user with a particular id -> GET: /users/:id
Delete login user -> DELETE: /users/me
Update user detail -> PATCH: /users/me
Upload user profile photo -> POST: /users/me/avatar
DELETE user profile photo -> DELETE: /users/me/avatar
Get user profile photo -> GET: /users/:id/avatar
