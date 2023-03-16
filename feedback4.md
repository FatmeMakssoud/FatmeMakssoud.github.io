
### Livrable n°1 : Feedback4 (Apprenant4)

#### Dossier : bapteme_php 

Ce fichier consiste d'un retour détaillé du tuteur qui a corrigé et évalué ton travail, il s'agit d'une évaluation des compétences et des attendus.

#### Correction du rendu 

#### Import Base de données

Tu as bien réussi la connexion entre PHP et le système de gestion des données Mysqladmin ainsi que la création de la base de données Skoule; tu as bien importé les données des tables.

#### Architecture MVC (Modèle - Vue - Contrôleur)

Tu a bien suivi la structure MVC en séparant les répertoires : Modèles, Vues et Contrôleurs. 

Concernant la partie controller, les fichiers "CoreController, ErrorController, MainController" n'ont pas été crées, même dans ceux crées, il existe des erreurs de syntaxe.

Par rapport aux vues, tu as crée cinq vues : appuser, main, error, student et teacher. Autres vues définies à terminer.

Concernant la partie Modèles, tu a crée tous les modèles avec (app/Models/AppUser.php). Dans le modèle AppUser, les fonctions publiques find() et update() sont vides (à terminer).
Concernant le modèle CoreModel, les méthodes getStatus() et setStatus() n'existent pas. 

La plupart des routes du fichier "routes.md" ont été configurées dans le fichier public/index.php. 

Concernant le fichier de config.ini: l'apprenant l'a bien crée et configuré.

#### Résultat et affichage 

Fonctionnellement, sur la page d'accueil, il y a des erreurs fatales qui s'affichent: ErrorController n'existe pas, etc..

#### Commentaires & Conseils

Je te propsose de relire tout le code et essayer de trouver une solution pour cette erreur fatal (création du contrôleur "ErrorController") etc.., en cas d'échec, adresses-toi à ton formateur pour lui demander de l'aide.


    
