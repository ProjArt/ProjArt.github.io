## Requête

`GET /me`


## Réponse

```javascript
    
    {
        "success":true,
        "message":"User found",
        "data":{
            "user": {
                "id": 1
                "username": "XXXXX",
                "created_at": "2022-05-22T15:10:33.000000Z",
                "updated_at": "2022-05-22T15:10:33.000000Z",
            }
        }
    }
    
```

## Erreurs

> `401` : Pas authentifier

```javascript

    { 
        "success": false,
        "message": "Unauthenticated",
        "data" : []
    }

```
