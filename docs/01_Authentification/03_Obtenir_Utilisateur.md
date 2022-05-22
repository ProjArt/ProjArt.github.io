# Obtenir l'utilisateur

## Requête

`GET /me`


## Réponse

```javascript
    
    {
        "success":true,
        "message":"User found",
        "data":{
            "user": {
                "username": "XXXXX",
                "updated_at": "2022-05-22T15:10:33.000000Z",
                "created_at": "2022-05-22T15:10:33.000000Z",
                "id": 8
            }
        }
    }
    
```

## Erreurs

> `404` : Pas trouvé

```javascript

    { 
        "success": false,
        "message": "Unauthenticated",
        "data" : []
    }

```
