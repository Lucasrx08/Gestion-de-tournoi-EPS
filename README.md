# Tournoi EPS

Gestionnaire visuel de tournois multisport conçu pour les enseignants d'EPS et les élèves.

## V1 disponible

- PWA responsive et installable.
- Sports et formats de pratique : basket 3x3/5x5, badminton, handball, football, volley, tennis de table, tennis, ultimate, rugby, hockey et activité personnalisée.
- Création rapide des équipes, joueurs et couleurs.
- Import CSV/TSV et copier-coller depuis Excel ou Google Sheets.
- Formules : championnat, élimination directe, 2 poules + phase finale, montante-descendante et ronde suisse.
- Vue visuelle des terrains avec grille adaptée au nombre de terrains.
- Démarrage global ou match par match.
- Chronos indépendants ou rotation commune.
- Matchs au temps, au score, score OU temps, ou libres.
- Score tactile +/− et arrêt automatique au score cible.
- Signal sonore de début et de fin via Web Audio.
- Modes Prof, Élève et TV.
- Fonction « Où je joue ? » pour les élèves.
- Classement en direct.
- Sauvegarde locale automatique et fonctionnement hors ligne après la première visite.
- Exports CSV, Excel compatible (.xls avec couleurs), JSON et impression/PDF.

## Hébergement

Le workflow `.github/workflows/pages.yml` déploie automatiquement la branche `main` sur GitHub Pages.

## Données

La V1 stocke les tournois localement dans le navigateur (`localStorage`). Aucun compte ni stockage distant de données élèves n'est requis.
