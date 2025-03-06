
----------------------------------------------------------------------------------
## merchants confirm-customer-withdrawal create
* Endpoint: `POST v1/merchants/customers/confirm-customer-withdrawal`
* Purpose: 

##Authorization

```json
API Key
```

> Body parameter

```json
 {
  "otp": "<string>",
  "tempId": "<string>"
}
```

> 200 Response
```json
{
  "otp": "<string>",
  "tempId": "<string>"
}
```
----------------------------------------------------------------------------------