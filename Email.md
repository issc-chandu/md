# Password Assistance
```
POST/v1/Forget_Password

```
## Request Headers
```
Content-Type : Appliction/Json

```
## Request Body
```
{

"Email" : "String"

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