# Connexion

## Requête

`POST /logout`

## Corps

```javascript

    {
        
    }

```

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