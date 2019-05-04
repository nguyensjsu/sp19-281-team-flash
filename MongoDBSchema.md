# Team Flash Project

## MongoDB Schema
  
### Project Modules
- User
- Admin
- Cart
- Order

## User Schema

```
var UserSchema = new Schema({  
    fname: { type: String, required: true
    },  
    lname: { type: String, required: true  
    },  
    email: { type: String, required: true  
    }, 
    password:{type:String, required: true  
    },
    type:{type:String}
});  
```

