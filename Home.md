# Home Page
```
POST/v1/Home Page

```

## Request Headers
```
Content- type : Application/Json

```
## Request Boby
```
{
    "Search_product" : "String",
    "Product_category" : "String",
    "Location" : "String"

}

```
## Response
```
200 - Success
Body 
{
"Result" : [
    {
       "Product_Id" : "Number",
       "Image" : "URL",
       "Product_name" : "String",
       "Product_price" : "Number",
       "Product_rating" : "String",
       "Product_discription" : "String"
    }
]
}
400 - Bad Request - Incorrect/Username/Email
403 - Forbidden
404 - Not Found
500 - Internal Server Error
304 - Not Modified


```