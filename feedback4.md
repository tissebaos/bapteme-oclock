#   Feedback 4 Bapteme JS

##  Structure et organisation du code et des fichiers source

La structure est assez bien gérée, tout de même le code ne couvre pas l'ensemble des fonctionnalités attendues 

##  Autres

Il serait judicieux de t'ameliorer sur les notions suivantes je t'es fourni avec quelques documentations Globalement 
- Gestions des rendus de templates [EJS](https://www.topcoder.com/thrive/articles/using-ejs-template-engine-with-express-js) 
- La gestion des requetes SQL [(doc. SQL)](https://sql.sh/cours/where)


- Lorsque tu fais appel à une fonction, il te faut vérifier si celle-ci prend des paramètres
- Lorsque tu fais appel a la fonction **"render"**, il n'est pas nécessaire de renvoyer un deuxième paramètre si celui-ci est un élément vide
```
  res.render('card',{
      
  });
```
idéalement, fais plutôt ceci *Tu as juste à renvoyer la view*
```
  res.render('card');
```

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
