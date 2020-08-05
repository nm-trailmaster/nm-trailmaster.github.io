## REST Endpoints

* `/trails`

    * `GET`
    
        * Request: (none)
        * Response: 
            * Body: `Trail[]`
    
    * `POST`
    
        * Request: 
            * Body: `Trail`
        * Response: 
            * Body: `Trail`
       
                
* `/quotes/{id}`

    * `GET`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `Trail`
    
    * `PUT`
    
        * Request 
            * Path 
                Body : `Trail`
        * Response                 
                
    * `DELETE`
    
        * Request 
            * Path 
                `id` : `long`
        * Response 
            * `404 (Deletion Succesful)`                