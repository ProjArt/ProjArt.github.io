# Connexion

## Requête

`GET /logout`

## Réponse

```javascript

   {
        "success": true,
        "message":"Logout succeed",
        "data": {
           
        }
    }

```

## Erreurs

> `401` : Pas autorisé

```javascript

    {
        "success": false,
        "message": "Unauthorized",
        "data" : []
    }

```