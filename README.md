Copy to the xampp htcdocs
Start by command promp php artisan serve

webAPI route

//display user name and only accept alphabet 
localhost:8000/api/users/{name?}
example
localhost:8000/api/users/anas

//display product by id and only accept numeric
http://localhost:8000/api/product/{id}
example
http://localhost:8000/api/product/1

//display current API method
http://localhost:8000/api/students

//display any API method
http://localhost:8000/api/posts

//display API get method
http://localhost:8000/api/profile

set in ProfileController for the function and display in view {name}.blade.php

Route

//Return full url in route
http://localhost:8000/user

declare the function in UserController

//Get app post from DB
http://localhost:8000/posts

//view post by id from DB in view
http://localhost:8000/posts/{id}
example
http://localhost:8000/posts/1

//Add new post
http://localhost:8000/add-posts

//edit post by id
http://localhost:8000/edit-post/{id}
example
http://localhost:8000/edit-post/1

//delete post by id
http://localhost:8000/delete-post/{id}
example
http://localhost:8000/delete-post/1

//update post by request body
Read the body pass and update 
