# Documentation du tuto GitHub avec Git

# Initialisation du dépôt

```bash
git init
git remote add origin HTTPS_REPO sinon SSH
```

## Rédiger un commit (bonne pratique)

```
Titre du commit 

Descrition de notre commit avec des informations sur 
l'évolution du projet
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Un commentaire"
git push origin main
```

## Création d'une branche
```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va
créer une branche, faire des modifications, les envoyer sur le dépôt, puis créer une
pull request pour demander une revue de code.


