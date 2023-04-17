#   Feedback 1 Bapteme JS

##  Structure et organisation du code et des fichiers source

De manière globale l'organisation des éléments est assez bien géré.   
Les noms des différentes variables sont assez significatifs ce qui aide à faciliter la lecture du code par d'autres dev 's
La gestion des erreurs mises en place est assez judicieuse

Les bouts de codes inutilisé "commenté" peuvent rendre le code complement touffu et difficile à consulter

## Gestion des requetes SQL

Les gestions des requêtes SQL présentent quelques lacunes (il serait judicieux d'améliorer les notions sur les conditions dans les requêtes SQL)   

Tu peux te documenter [ici (doc. SQL)](https://sql.sh/cours/where) 

## Variables et Constantes

Globalement il est plus judicieux d'éviter de réaffecter la valeur d'une constante, si la valeur doit obligatoirement être réaffecté il vaut mieux utiliser une variable (privilégier la declaration avec **let**)

Lorsque tu fais de la concatenation il faut t'assurer que les éléments peuvent être converti en chaine de caractère

##  Autres

L'utilisation des méthodes asynchrones est très bien il permet d'éviter les callbacks qui peuvent être très pénible a géré

## validations du projet

### L'utilisateur doit pouvoir

- Lister les cartes sur la page d'accueil
- Consulter les détails d'une carte
- Ajouter une carte au deck
- retirer une carte du deck
- le nombre de cartes dans le deck doit être limité à 5 cartes maximum
- Afficher l'ensemble des cartes présentes dans le deck
- Rechercher les cartes par niveau
- Rechercher les cartes par Valeur (Direction et valeur)
- Rechercher les cartes par nom
- Rechercher les cartes par Element