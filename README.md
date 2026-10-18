# MitiQloUIZ Expédition 33 2026

Projet prêt à l'emploi pour déploiement Git & Vercel.

## Arborescence du projet

- `public/index.html` : Code principal du site.
- `public/pictos.json` : Base de données des joueurs et pictogrammes associés.
- `public/pictos/` : Dossier contenant les images (`ED.png`, `FA.png`, `LS.jpg`, `P.png`, `TM.png`, `TT.png`, `VA.png`).
- `vercel.json` : Fichier de configuration Vercel pour servir le dossier `public`.

## Guide de mise en ligne

### 1. Préparation locale
1. Dézipz l'archive ZIP.
2. Copiez vos 7 fichiers d'images (`ED.png`, `FA.png`, `LS.jpg`, `P.png`, `TM.png`, `TT.png`, `VA.png`) directement dans le dossier `public/pictos/`.

### 2. Publication sur GitHub
Dans votre terminal à la racine du projet :
```bash
git init
git add .
git commit -m "Initial commit - MitiQloUIZ Expédition 33 2026"
git branch -M main
git remote add origin https://github.com/VOTRE_NOM_UTILISATEUR/mitiqlouiz-expedition33.git
git push -u origin main
```

### 3. Déploiement sur Vercel
1. Rendez-vous sur [Vercel.com](https://vercel.com) et connectez-vous.
2. Cliquez sur **Add New** > **Project**.
3. Sélectionnez votre dépôt GitHub `mitiqlouiz-expedition33`.
4. Laissez les options par défaut et cliquez sur **Deploy**.
