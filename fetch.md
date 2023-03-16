

### Livrable n°2 : le conseil technique avancé à un.e apprenant.e

### Méthode fetch() adressée à l'apprenant 2


La méthode fetch en PHP est utilisée pour récupérer une ligne de données à partir d'un jeu de résultats après l'exécution d'une requête SQL. 
Cette méthode est couramment utilisée avec l'extension PDO (PHP Data Objects), qui fournit une interface pour accéder aux bases de données en utilisant une syntaxe commune.

En termes simples, fetch est utilisée pour extraire des données d'une base de données après qu'une requête a été exécutée. Lorsque tu exécutes une requête, une ressource de jeu de résultats est renvoyée, qui contient toutes les lignes de données qui correspondent à la requête.

La méthode fetch est utilisée pour extraire une ligne de données à la fois de ce jeu de résultats. Chaque fois que tu appeles fetch, elle renvoie la ligne suivante du jeu de résultats sous la forme d'un tableau associatif. Tu peux ensuite accéder aux données dans ce tableau en utilisant les noms de colonnes de la requête.


#### Connexion à la base de données 

$pdo = new PDO('mysql:host=localhost;dbname=mydatabase', 'username', 'password'); 

 .#### Exécution de la requête pour récupérer tous les eleves
 
 $query = $pdo->query('SELECT * FROM student');

#### Boucle pour parcourir toutes les lignes de données du jeu de résultats

while ($row = $query->fetch(PDO::FETCH_ASSOC)) {
    // Affichage des données de chaque utilisateur
    echo 'ID: ' . $row['id'] . '<br>';
    echo 'First Name: ' . $row['firstname'] . '<br>';
    echo 'Last Name: ' . $row['lastname'] . '<br>';
}

Dans cet exemple (code intégré dans la vue "student"), tu te connectes à la base de données MySQL, exécutes une requête pour récupérer tous les étudiants dans la table "student", puis tu utilises une boucle while pour parcourir chaque ligne de données du jeu de résultats. Pour chaque ligne, tu affiches les valeurs de chaque colonne à l'aide du tableau associatif retourné par fetch.

Il est important de noter que fetch renvoie false lorsqu'il n'y a plus de lignes de données à extraire du jeu de résultats. Il est donc courant d'utiliser une boucle while pour parcourir toutes les lignes de données jusqu'à ce que fetch retourne false.