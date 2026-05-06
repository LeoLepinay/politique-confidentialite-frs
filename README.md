# Politique de confidentialite - Fantasy Realms Scoring

Mini-projet web statique dedie a la page de politique de confidentialite pour Google Play.

## Fichiers
- index.html : page de politique de confidentialite
- styles.css : style responsive

## Personnalisation
1. Ouvrir index.html
2. Remplacer TON_EMAIL_DE_CONTACT par votre adresse email
3. Mettre a jour la date de derniere mise a jour si necessaire

## Hebergement Vercel (recommande)

### Methode 1 : Tableau de bord Vercel (la plus simple)
1. Creer un depot GitHub et pousser ce dossier a la racine du depot
2. Aller sur Vercel, cliquer sur Add New > Project
3. Importer le depot GitHub
4. Laisser les reglages par defaut (aucun build requis)
5. Cliquer sur Deploy

### Methode 2 : Vercel CLI
1. Installer la CLI : `npm i -g vercel`
2. Dans ce dossier, lancer : `vercel`
3. Repondre aux questions interactives (projet statique)
4. Pour la mise en production : `vercel --prod`

### Fichier de configuration
- `vercel.json` est deja fourni pour des URLs propres et des en-tetes de securite de base.

## URL a utiliser dans Google Play
Renseigner l'URL publique de index.html dans le champ de politique de confidentialite de la Play Console.
