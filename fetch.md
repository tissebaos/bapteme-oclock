# Feedback Fetch

**fetch** est une fonction qui lorsque tu l'appelles te renvoie une promesse *(une promesse c'est un type de donnée JavaScript comme le JSON, les Tableaus ...)*

basiquement on l'ecrira comme ceci

```
fetch('http:url.com')
.then(function(response) {
    return response.JSON();
})
.then(function(data) {
    console.log(data)
});
```

dans cet exemple, on a deux fonctions appelées **t** dont la première se charge, récupérer notre promesse *(celle dont on parlait plus haut)* puis de la renvoyer sous forme de JSON pour ce qui est de notre exemple quant à la deuxième elle va récupérer le JSON renvoyé par le premier qui sera à ce moment converti en objet JSON

- Le paramètre *data* de notre exemple correspond à la valeur renvoyée par le **return response.JSON();**
- Le paramètre *response* présent dans le premier then correspond au résultat de la requête exécutée par la fonction **fetch**

