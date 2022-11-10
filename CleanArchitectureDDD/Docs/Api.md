# CA&DDD API 

-   [CA&DDD API] (#cd&ddd-api)
    -   [Auth] (#auth)
        -   [Register] (#register)
            -   [Register Request] (#register-request)
            -   [Register Response] (#register-response)
        -   [Login] (#login)
            -   [Login Request] (#login-request)
            -   [Login Response] (#login-response)

## Auth 

### Register 

```js
POST {{host}}/auth/register
```

### Register Request 
```json
{
    "firstName": "Cristian", 
    "lastName": "Martínez", 
    "email": "crismh2@hotmail.com",
    "password": "Prueba123"
}
```