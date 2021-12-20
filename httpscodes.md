//errors and http response codes 

2xx -> success 

200 : operation succeeded
201 : success  , resource created 

3xx -> redirect

301 : moved permanently

4xx -> something happened or error occured by the client side 

401 : not authenticated 
402 : not authorized 
403 : not found
404 : not found
422 : Invalid input

5xx -> 500 : server side error


// http methods 

get => get a resource from the server 

post => post a resource to the server  i.e. create or append resource 

put => put a resorce onto the sever i.e. create or overwrite a resource 

patch => update parts of an existing resource on the server

delete => delete a resource on the server 

options => determine whether follow up request is allowed 