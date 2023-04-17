#   Feedback 3 Bapteme JS

##  Structure et organisation du code et des fichiers source

La structure est assez bien géré, tout de meme le code ne couvre pas l'ensemble des fonctionalités attendus 

Le nomage des fonctions n'est pas tres explicite   
Le nom de la function doit etre le proche possible de l'action que realise cette fonction

##  Autres

Globalement les notions de bases ne sont pas assez bien maitrisé
- Gestions des rendus de templates [doc EJS](https://www.topcoder.com/thrive/articles/using-ejs-template-engine-with-express-js) 
- La gestion des requetes SQL [(doc. SQL)](https://sql.sh/cours/where) et n'hesite a me poser tes questions


### Page Detail de carte  
- Les valeurs *(variables, constantes, tableau ...)* envoyé a la view sont un peu comme des parametres (mais des parametres ou le nom que tu envoie est le meme nom que tu va utiliser dans la view)
- Afin de pouvoir placer une boucle sur la "variable" qui est envoyé vers la view il faut celle-ci soit iterable *ex: (un Tableau, objet JSON, chaine de caractere...)*
- La boucle placé sur la variable card ne fonctionne pas car la variable *card* n'est pas un element iterable 
- Il serait plus judicieux d'utiliser ParseInt pour le cast de ta variable en nombre

###

## validations du projet

### L'utilisateur doit pouvoir

- [x] Lister les cartes sur la page d'accueil : **OK**
- [ ] Consulter les détails d'une carte 
- [ ] Ajouter une carte au deck 
- [ ] retirer une carte du deck
- [ ] le nombre de cartes dans le deck doit être limité à 5 cartes maximum
- [ ] Afficher l'ensemble des cartes présents dans le deck
- [ ] Rechercher les cartes par niveau
- [ ] Rechercher les cartes par Valeur (Direction et valeur)
- [ ] Rechercher les cartes par nom
- [ ] Rechercher les cartes par Element
