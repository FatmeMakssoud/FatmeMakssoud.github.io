
### Livrable n°4 : retour sur un MCD d'un apprenant

Dans la méthodologie Merise destinée à créer des bases de données, il existe des outils dédiés aux traitements et aux données. Le MCD est une représentation graphique de haut niveau qui permet facilement et simplement de comprendre comment les différents éléments sont liés entre eux.

#### Evaluation du MCD reçu 

Le modèle conceptuel de données MCD reçu de la part d'un apprenant concerne la création d'une page web de type platforme e-commerce d'achat de mug O'clock, ce modèle est bien fait, il existe une erreur dans les cardinalités des entités "USER" et "PRODUCT".

En fait, un user peut liker un ou plusieurs produits donc ia cardinalité du côté USER est (1, N), également pour celle de l'autre côté du produit, un produit peut être liker une ou plusierus fois (1, N).

Toutes les autres entités (ADDRESS, ORDER) ainsi que les cardinalités entre ces entités sont correctes.

N.B: Il existe plusieurs outils pour la réalisation des modèles conceptuels de données ou la modélisation de bases de données  comme: AnalyseSI, MySql Workbench, GitMind, ChartEdra, Draw.io ..

