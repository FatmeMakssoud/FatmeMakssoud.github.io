
### Livrable n°1 : Feedback1 (Apprenant1)

#### Dossier bapteme_php 

Ce fichier consiste d'un retour détaillé du tuteur qui a corrigé et évalué ton travail, il s'agit d'une évaluation des compétences et des attendus.

#### Correction du rendu 

#### Import Base de données

Tu as bien réussi la connexion entre PHP et Mysqladmin ainsi que la création de la base de données Skoule; tu as bien importé les données des tables.

#### Architecture MVC (Modèle - Vue - Contrôleur)

Tu as bien suivi la structure MVC ainsi que les organisations des fichiers dans cette architecture en créant tous les contrôleurs notamment 
CoreController.php, StudentController.php, etc. Cependant, ton code est incomplet, il te manque plusieurs méthodes propres à chaque contrôleur, par exemple, 
dans UserController : méthode qui s'occupe des données envoyées en POST par le formulaire de modification, celle qui s'occupe de la mise à jour d'un user ainsi de sa suppression n'existent pas, etc..

Tu as aussi crée toutes les vues demandées qui sont présentes dans le dossier app/Views mais elles sont incomplètes par exemple, tu n'as pas crée le fichier "add-update.tpl.php" dans la vue "appuser" qui te permet d'ajouter et de modifier un utilisateur.

Egalement, les  modèles ont été crées (app/Models/AppUser.php, etc..), comme pour les contrôleurs, plusieurs méthodes dans le modèle "Appuser" n'ont pas 
été ajoutées comme celles qui permettent l'ajout, la mise à jour et la suppression d'un enregistrement dans la table app_user, en plus, l'authentifiacation ne fonctionne pas.

Toutes les routes demandées dans le fichier "routes.md" ont été bien configurées dans le fichier public/index.php. Cependant sur le navigateur, 
les vues ne s'affichent pas sur les routes configurées.

Concernant le fichier de config.ini: tu l'as bien crée et configuré.

#### Résultat et affichage 

Fonctionnellement, à la page d'accueil du site, on voit qu'une page d'erreur (404) qui s'affiche avec deux onglets sur la barre de navigation 
(Skoule qui nous ramène à la page localhost et Se connecter qui est non fonctionnel).

#### Commentaires & Conseils

Révise ton code surtout les vues (rendu), la communication entre ces dernières et les contrôleurs ainsi que la partie authentifiaction.