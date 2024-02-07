Documentation du tuto GitHub avec git

## Initialisation du dépôt

'''bash
git init
git remote add origin git@github.com:phil3269/git_test.git
'''

## Rédiger un commit

'''
Titre du commit

Description de notre commit avec des informations sur l'évolution du projet
'''

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Titre du commentaire"
git push origin master
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```