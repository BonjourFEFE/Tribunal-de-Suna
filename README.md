# Justice — Tribunal de Sunagakure

Site de gestion pour un RP Naruto : membres et grades, trésorerie, jugements et tâches.
Tout tient dans un seul fichier : `index.html` (HTML, CSS et JavaScript).

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
