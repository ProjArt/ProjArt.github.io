# Documentation

## Configuration

- Installer Daux 

``` composer global require daux/daux.io ```


## Utilisation 

- Ecrire des fichier md dans docs

- Générer les fichiers HTML 

```daux generate ```

- Publier le dossier static sur la branch gh-pages

```git add . && git commit -m 'update' && git subtree push --prefix static origin gh-pages ```

- Publier ses changements sur la branch main

```git push ```
