# - Une application qui t'aide à étudier ton instrument

## But de l'application
Notre application mobile est destinée aux musiciens qui veulent améliorer leur régularité et leur efficacité pendant l'étude de leur instrument.
Le but est d'avoir une aide simple pour pouvoir: 
- Organiser et suivre chaque séance d'étude
- Ajouter ton répertoires ainsi que les observations faites par le professeur et tous les détails pour chaque morceau dans un espace de notes (journal)
- Avoir un espace de statistique pour pouvoir analyser ton progrès
- Augmenter ta motivation en voyant tes progrès

## Choix technologiques

| Domaine | Choix | Justification |
|----------|-------|----------------|
| Design | Figma | Facile à utiliser pour créer le design |
| Frontend | React Native et JavaScript | Développement rapide, code simple, intégration facile de composants audio |
| Backend | - | - |
| Base de données | - | - |

## Structure de l’application
### Écrans principaux

| Écran | Description | Fonctionnalités |
|--------|--------------|-----------------------------|
| Home page | Vue d’ensemble de la journée et des objectifs. | - Temps de pratique du jour<br>- Streak de régularité<br>- Bouton “Démarrer une séance” |
| Séance de pratique | Interface minimaliste pendant la pratique. | - Chronomètre / pause / arrêt<br>- Notes de séance<br>- Ajout d’un enregistrement audio<br>- Accès rapide : métronome, accordeur |
| Répertoire | Gestion des morceaux ou exercices. | - Liste de pièces<br>- Progression individuelle<br>- Historique des séances et enregistrements |
| Statistiques | Suivi de la progression globale. | - Graphiques : temps total, régularité, répartition par type de pièce<br>- Historique des pratiques (calendrier) |
| Profil et paramètres | Gestion des préférences utilisateur. | - Objectif quotidien<br>- Instruments pratiqués<br>- Export ou réinitialisation des données |
