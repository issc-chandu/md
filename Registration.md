# Registration

POST/v1/Registration

## Request Holders
```
Content-Type : Application/Json

```
## Request Boby
```
"Name : "String",
"Mobile No : "Number",
"Email : "String",
"Password' : "String",
"Comfirm Password" : "String:

```
## Response

```
200 - Success
Boby
{
    "Username" : "String"
}
400 - Bad Request - Incorrect/Username/Email
403 - Forbidden
404 - Not Found
500 - Internal Server Error
304 - Not Modified

```