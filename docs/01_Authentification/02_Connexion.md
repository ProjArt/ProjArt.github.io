# Connexion

## Requête

`POST /login`

## Corps

```javascript

    {
        "username": "XXXXX",
        "password": "XXXXX"
    }

```

## Réponse

```javascript

   {
        "success": true,
        "message":"Login validated",
        "data": {
           "access_token": "XXXXX",
           "token_type": "Bearer"
        }
    }

```

## Erreurs

> `401` : Pas autorisé
