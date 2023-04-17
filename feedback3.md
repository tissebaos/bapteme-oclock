#   Feedback 3 Bapteme JS

##  Structure et organisation du code et des fichiers source

La structure est assez bien gérée, tout de même le code ne couvre pas l'ensemble des fonctionnalités attendues 

Le nommage des fonctions n'est pas très explicite, le fait d'avoir des variables et des fonctions assez bien nommées facilite aussi grandement la lecture du code

##  Autres

Globalement, les notions de base ne sont pas assez bien maîtrisées
- Gestion des rendus de templates [doc EJS](https://www.topcoder.com/thrive/articles/using-ejs-template-engine-with-express-js) 
- La gestion des requêtes SQL [(doc. SQL)](https://sql.sh/cours/where) et n'hésite pas à me poser tes questions

### Page Detail de carte  
- Les valeurs *(variables, constantes, tableau...)* envoyées à la view sont un peu comme des paramètres (mais des paramètres ou le nom que tu envoies est le même nom que tu vas utiliser dans la view)
- Afin de pouvoir placer une boucle sur la "variable" qui est envoyée vers la view il faut celle-ci soit itérable *ex : (un Tableau, objet JSON, chaîne de caractère...)*
- La boucle placée sur la variable card ne fonctionne pas, car la variable *card* n'est pas un élément itérable 
- Il serait plus judicieux d'utiliser ParseInt pour le caste de ta variable en nombre

###

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
