
### Livrable n°1 : Feedback3 (Apprenant3)

#### Dossier : bapteme_php 

Ce rendu consiste d'un retour détaillé du tuteur qui a corrigé et évalué ton travail, il s'agit d'une évaluation des compétences.

#### Correction du rendu 

#### Import Base de données

Pour l'imporation de la base, tu as bien réussi la connexion entre PHP et le SGBD Mysqladmin ainsi que la création de la base de données Skoule; Les données des tables ont été bien importées.

#### Architecture MVC (Modèle - Vue - Contrôleur)

Tu as bien suivi la structure MVC en séparant les parties : Modèles, Vues et Contrôleurs.

Concernant la partie controllers, les fichiers "CoreController" n'existe pas ainsi que celui des users.

Par rapport aux vues, tu n'as pas crée que quatre vues : main, error, student et teacher.

Le  modèle pour les users n'a pas été ajouté (app/Models/AppUser.php).

Cinq routes du fichier "routes.md" ont été configurées dans le fichier public/index.php. 

Concernant le fichier de config.ini: tu l'as bien crée et configuré.

#### Résultat et affichage 

Fonctionnellement, sur la page d'accueil, il y a qu'une page d'erreur (404) qui s'affiche.

Malgré les configurations des cinq routes, les vues ne sont pas affichées sur la page de navigation.

#### Commentaires & Conseils

Révise le code surtout les vues (rendu), la communication entre ces dernières et les contrôleurs ainsi que la partie authentifiaction.
    
