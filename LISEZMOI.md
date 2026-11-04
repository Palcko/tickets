# Appli Tickets : installation (10 étapes)

Une seule fois, sur ordinateur (avec Claude pour t'accompagner) :
1. Créer un compte gratuit sur github.com (ou te connecter).
2. Créer un dépôt public nommé `tickets`.
3. Y envoyer tous les fichiers du dossier `AppTickets` (bouton « Add file » > « Upload files »). Le fichier `opencv.js` fait 10 Mo : c'est normal.
4. Dépôt > Settings > Pages > « Deploy from a branch » > `main` / `(root)` > Save. Après 1 minute, l'adresse est `https://TON-PSEUDO.github.io/tickets/`.
5. Google Cloud (console.cloud.google.com, compte saunier.damien.sd@gmail.com) : créer un projet, activer « Google Drive API », créer un « ID client OAuth » de type « Application Web », avec l'origine autorisée `https://TON-PSEUDO.github.io`. Écran de consentement : « Externe », ajouter ton adresse comme utilisateur test.
6. Copier l'ID client (finit par `.apps.googleusercontent.com`, ce n'est pas un secret) dans le fichier `config.js`, puis renvoyer ce fichier sur GitHub.

Sur le téléphone Android :
7. Ouvrir l'adresse dans Chrome.
8. Menu ⋮ > « Installer l'application » (ou « Ajouter à l'écran d'accueil »).
9. Ouvrir « Tickets », photographier un ticket, vérifier les 4 coins, remplir, Enregistrer.
10. Appuyer sur « Envoyer maintenant » : choisir ton compte Google et accepter (la 1re fois). Les tickets arrivent dans Drive > dossier « Tickets ».

Pour l'autre session Claude : lire le dossier Drive « Tickets » (`Ticket_….jpg` + `Ticket_….json` du même nom). Après saisie dans Gestan, déplacer le jpg dans le sous-dossier « Saisis » : l'appli passera le ticket à « Saisi dans Gestan ».
