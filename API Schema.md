# Team Flash Project

## API Schema

### Project Modules
- User
- Admin
- Cart
- Order

## User 

### POST /user
```
This api is used for Login
POST /login HTTP/1.1
Accept: application/json

Body : {
    "username" :"admin@gmail.com",
    "password" :"admin"
}
```

### POST /user
```
This api is used for Registering user
POST /signup HTTP/1.1
Accept: application/json

Body : {
    "username" :"admin@gmail.com",
    "password" :"admin",
    "name":"admin"
}
```

### GET /user
```
This api is used for getting all the items from inventory
GET /inventory HTTP/1.1
Accept: application/json

Response:
- 204 No Content
- 404 Not Found
- 200 Success
```


