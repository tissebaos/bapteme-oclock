#   Feedback 2 Bapteme JS

##  Structure et organisation du code et des fichiers source

La structure est assez bien géré, tout de meme le code ne couvre pas l'ensemble des fonctionalités attendus 

Le nomage des fonctions n'est pas tres explicite   
Le nom de la function doit etre le proche possible de l'action que realise cette fonction


##  Autres

Globalement les notions de bases ne sont pas assez bien maitrisé
- Gestions des rendus de templates [EJS](https://www.topcoder.com/thrive/articles/using-ejs-template-engine-with-express-js) 


- Pour parser une donner en entier il est plus judicieux d'utiliser **ParseInt**  au lieu de *Number*
- Pour chaque route existante doit etre créée son controller
- 

##  Page Detail de carte

- Depuis la page de details d'une carte l'utilisateur doit pouvoir egalement l'ajouter au deck

## Resultats de recherche

- Les controllers des routes */search/level*, */search/name*, */search/values* n'ont pas été créé 

## Construction du deck

- Lorsque tu recupere les elements du deck de la session il te faut avant de rajouter un nouvel element verifier le nombre de cartes present dans le deck afin de ne pas depasser le max de 5 cartes dans le deck

##  Validations du projet

### L'utilisateur doit pouvoir

- [x] Lister les cartes sur la page d'accueil : **OK**
- [x] Consulter les détails d'une carte : **OK**
- [x] Ajouter une carte au deck : **OK**
- [ ] retirer une carte du deck
- [x] le nombre de cartes dans le deck doit être limité à 5 cartes maximum
- [x] Afficher l'ensemble des cartes présents dans le deck : **OK**
- [ ] Rechercher les cartes par niveau
- [ ] Rechercher les cartes par Valeur (Direction et valeur)
- [ ] Rechercher les cartes par nom
- [ ] Rechercher les cartes par Element
