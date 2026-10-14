# Justice — Tribunal de Sunagakure

Site de gestion pour un RP Naruto : membres et grades, trésorerie, jugements et tâches.
Tout tient dans un seul fichier : `index.html` (HTML, CSS et JavaScript).

## Accès
- Le gérant se connecte avec son mot de passe de base (modifiable depuis l'onglet Profil).
- Pour ajouter quelqu'un : onglet Membres > prénom, nom, grade > « Ajouter à la whitelist ».
- La personne clique sur « Créer mon sceau » sur la page de connexion, saisit son prénom et son nom,
  puis choisit son mot de passe si son nom est dans la whitelist.

## Lancer en local
Ouvre le dossier dans VS Code, puis clic droit sur `index.html` > « Open with Live Server ».

## Déploiement sur Vercel
1. Importe ce dépôt sur https://vercel.com/new
2. Framework Preset : **Other** (aucune commande de build, aucun dossier de sortie)
3. Clique sur **Deploy**

Ensuite, chaque `git push` sur la branche `main` redéploie le site automatiquement.

## Important
Hors de claude.ai, les données sont enregistrées dans le navigateur de chaque visiteur
(localStorage). Elles ne sont donc pas partagées entre les membres. Pour un usage à
plusieurs, il faut ajouter un serveur et une base de données.
