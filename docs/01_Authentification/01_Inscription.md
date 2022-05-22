# Inscription

## Requête

`POST /register`

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
        "message": "Register validated",
        "data": {
            "access_token": "XXXXXX",
            "token_type": "Bearer"
        }
    }

```

## Erreurs

> `401` : Pas autorisé
