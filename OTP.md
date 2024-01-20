# OTP

```
POST/v1/OTP

```
## Request Body
```
Content-Type :Appliaction/Json

```
## Request Headers

```
"OTP" : "Number",

```
## Response
```
200 - Success
400 - Bad Request - Incorrect/Username/Email
403 - Forbidden
404 - Not Found
500 - Internal Server Error
30 - Not Modified

```