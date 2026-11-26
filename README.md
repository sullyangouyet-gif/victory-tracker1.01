# Victory Tracker — prototype

Prototype front-end statique (HTML/CSS/JavaScript), sans dépendance.

## Lancer
Ouvrir `index.html` dans un navigateur ou publier le dossier sur un hébergement statique.

## État actuel
- Interface responsive style esport.
- Navigation Événements / Leaderboards / Actualités.
- Filtres de démonstration région, plateforme et recherche.
- Classement et événements explicitement fictifs : aucune donnée réelle n'est revendiquée.

## Prochaine étape : données réelles
La Data API publique Epic documentée ici concerne les métriques agrégées des îles :
https://dev.epicgames.com/documentation/fortnite/using-fortnite-data-api-in-fortnite

Elle ne fournit pas à elle seule le calendrier compétitif et les leaderboards de tournois.
Il faudra sélectionner une source autorisée pour les événements et résultats, vérifier ses conditions d'utilisation, puis connecter un backend/proxy si une clé API est nécessaire. Ne jamais placer une clé secrète dans le JavaScript du navigateur.
