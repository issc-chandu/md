# New Password
```
Post/v1/Appliction

```
## Request Headers
```
Content-Type :Appliction/Json
```
## Resquest Body
```
{
"Email" : "String",
"New Password" : "String",
"Conform Password" : "String"
}
```
## Response
```
200 - Success
400 - Bad Request - Incorrect/Username/Email
403 - Forbidden
404 - Not Found
500 - Internal Server Error
304 - Not Modified

```