# Instructions pour déployer votre portfolio sur GitHub Pages

## Étape 1 : Créer un dépôt GitHub
1. Allez sur https://github.com et connectez-vous
2. Cliquez sur "+" → "New repository"
3. Nom du dépôt : `reddad-chaouay-portfolio` (ou le nom de votre choix)
4. Cochez "Public" (important pour GitHub Pages gratuit)
5. Cliquez sur "Create repository"

## Étape 2 : Activer GitHub Pages
1. Dans votre dépôt, allez dans "Settings"
2. Dans le menu de gauche, cliquez sur "Pages"
3. Sous "Build and deployment", sélectionnez "Deploy from a branch" (sélectionnez branche `main` et dossier `/ (root)`), ou "GitHub Actions"
4. GitHub Pages est maintenant activé !

## Étape 3 : Pousser votre code
Exécutez ces commandes dans votre terminal :

```bash
git remote set-url origin https://github.com/redinho2002/reddad-chaouay-portfolio.git
# ou si vous n'avez pas encore d'origin :
# git remote add origin https://github.com/redinho2002/reddad-chaouay-portfolio.git
git branch -M main
git push -u origin main
```

## Étape 4 : Déploiement
1. GitHub va automatiquement déployer votre site (2-3 minutes)
2. Allez dans "Settings" → "Pages" pour voir l'URL
3. Votre portfolio sera disponible à : `https://redinho2002.github.io/reddad-chaouay-portfolio/`

## Étape 5 : Partager votre lien !
Utilisez ce lien sur votre profil LinkedIn :
```
https://redinho2002.github.io/reddad-chaouay-portfolio/
```
