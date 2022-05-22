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

> `422` : Unprocessable Entity

```javascript

    {
       "success": false,
       "message": "The XXXX field is required."
    }
    
```
