
### Livrable n°1 :Feedback2 (Apprenant2)

#### Dossier : bapteme_php 

Ce fichier consiste d'un retour détaillé du tuteur qui a corrigé et évalué ton travail, il s'agit d'une évaluation des compétences et des attendus.

#### Correction du rendu 

#### Import Base de données

Tu as bien réalisé la connexion entre PHP et le système de gestion des données Mysqladmin ainsi que la création de la base de données Skoule; tu as bien importé les données des tables.

#### Architecture MVC (Modèle - Vue - Contrôleur)

Tu as bien suivi la structure MVC en séparant les parties : Modèles, Vues et Contrôleurs.
Concernant la partie controller, tous les fichiers sont présents sauf que la plupart des méthodes n'ont pas été implémentées, notamment, teacherUpdateGet, studentDelete, etc..

Par rapport aux vues, tu n'as pas crée la vue des utilisateurs (dossier : app/Views). Egalement, le  modèle pour les users n'a pas été ajouté (app/Models/AppUser.php).

Seulement quatre routes demandées dans le fichier "routes.md" ont été bien configurées dans le fichier public/index.php. 

Concernant le fichier de config.ini: tu l'as bien crée et configuré.

#### Résultat et affichage 

Fonctionnellement, toute la page (vues) s'affiche juste la partie d'authentification et de droits d'accès n'ont pas été faits.

La page des "profs" s'affichent normalement avec la prise en compte des données fournies dans la base, mais la modification et la suppression d'un membre n'est pas possible. L'onglet "Etudiants" est fonctionnel sans la possibilité de modification et de suppression.

Comme tu n'as pas crée la route et la vue "users", l'onglet "utilisateurs" n'est pas cliquable.
    
#### Commentaires & Conseils

Tu as réalisé un bon travail et je te conseille de terminer ton code notamment les vues: profs, Etudiants" et Utilisateurs (modification, ajout et suppression).