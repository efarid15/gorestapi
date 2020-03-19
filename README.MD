Golang Rest API JWT Kick Starter

========================================================

End point : POST /api/user/new
{"email" : "xxx@example.com", "password" : "secret"}

GET /api/user/login
{"email" : "xxx@example.com", "password" : "secret"}

POST /api/contacts/new
{"name" : "your name", "phone" : "your phone"}

Header Authorization : Bearer "login token"

GET /api/me/contacts

Header Authorization : Bearer "login token"

=======================================================

Make Your .env file with this variable

db_name = 
db_pass = 
db_user = 
db_type = 
db_host = 
db_port = 
token_password = 
