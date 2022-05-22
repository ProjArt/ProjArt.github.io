## Bienvenue

Voici la documentation pour communiquer avec le back-end de l'application ProjArt - TGV

Le back-end utilise le framework Laravel et respecte le mieux possible les conventions d'une REST API

> L'url de base est https://projart-tgv.pingouin.heig-vd.ch/api

> Pour toutes les requêtes, ajoutez les headers suivant : 

Le token se récupère grâce aux routes de [Connexion](01_Authentification/02_Connexion.md) ou d'[Inscription](01_Authentification/01_Inscription.md).

```

    {
        "Accept" : "application/json",
        "Authorization": "Bearer XXXXXXX"
    }

```
