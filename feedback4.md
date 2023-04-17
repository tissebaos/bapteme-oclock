#   Feedback 4 Bapteme JS

##  Structure et organisation du code et des fichiers source

La structure est assez bien géré, tout de meme le code ne couvre pas l'ensemble des fonctionalités attendus 

Le nomage des fonctions n'est pas tres explicite   
Le nom de la function doit etre le proche possible de l'action que realise cette fonction

##  Autres

Il serait judicieux de t'ameliorer sur les notions suivantes je t'es fourni avec quelques documentations Globalement 
- Gestions des rendus de templates [EJS](https://www.topcoder.com/thrive/articles/using-ejs-template-engine-with-express-js) 
- La gestion des requetes SQL [(doc. SQL)](https://sql.sh/cours/where)


- Lorsque tu fait appel a une fonction il te faut verifier si celle prends des parametres
- Lorsque tu fait appel a la fontion render il n'est pas necessaire de renvoyer un deuxieme parametre si celui ci est un element vide
```
  res.render('card',{
      
  });
```
idealement fait plutot ceci *tu as juste a renvoyer la view*
```
  res.render('card');
```

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
