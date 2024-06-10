## GET (Requesting Something)
If you are doing a GET:

- Make sure the HTTP Method is GET
- URL should come after the HTTP Method
- No headers needed
- No body needed
- If you are trying to get ALL (an array) do not put an ID at the end.
- If you are trying to get ONE (an array) you need to put an ID at the end.

## POST (Insert)

If you are doing a POST:

- Make sure the HTTP Mythod is POST (Not GET)
- You don't want a id in the URL
- You need an HTTP header to tell the server about the content-type 
```http
Content-Type: application/json
```
- You need a JSON object in the body 
- JSON object can not have a trailing comma after the last property (it is generated on the server by the API)
- JSON objects can not have a trailing comma after the last property 

## PUT (Update)

If you are doing a PUT

- Make sure the HTTP Mythod is PUT (Not Get or POST)
- you DO want an id in the URL
- You need an HTTP header to tell the server about the content-type 
```http
Content-Type: application/json
```
- You need a JSON object in the body 
- JSON object can not have a trailing comma after the last property (it is generated on the server by the API)
- JSON objects can not have a trailing comma after the last property 

## DELETE (Delete)

If you are doing a DELETE

- Make sure the HTTP Method is DELETE
- URL should come after the HTTP Method
- You need to put an id at the end
- No headers needed
- No body needed