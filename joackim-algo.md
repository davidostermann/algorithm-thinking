# Les algo c'est beau

### Exercice 1 : La machine à qui vous donner des ordres :

## Je veux que la machine
- Allume la console
- Classer les noms des élèves d'une classe de z à a

## Ma machine possède
- Une mémoire (par défaut)
- Une camera
- Des ports pour connecter l'ordinateur à la console
- Un écran
- multimetre

## Ordres
- Connecter l'ordinateur à la console
- On estime que la console est allumée si les ampères dépassent 15
- Soit la console est déjà allumée et tu sors de la boucle soit elle est éteinte, tu incrémentes ampereRetour, tu allumes la console et tu sors de la boucle

```
1. Écrire 0 dans une variable ampere
2. Écrire 0 dans une variable : ampereRetour
3. Écrire false dans une variable onOrOff
4. Tant que ampereRetour est égal à 0 faire une boucle pour vérifier si la console est éteinte
5. Lancer la fonction checkAmpere qui mesure les ampères de la console, retourner la valeur des ampères dans une variable ampereRetour
6. Si ampereRetour supérieur ou égal à 15 changer la valeur de onOrOff en true
7. Afficher 'La console est allumée'
8. Mettre ampere = ampereRetour
9. Sinon si ampereRetour est égal à 0
10. Pour iteration jusqu'à 15 incrémenter ampereRetour pour alimenter la console
11. À la fin du POUR afficher que la console est allumée
12. Mettre ampere = ampereRetour

```

### Exercice 2 : L'ordinateur à qui vous donner des ordres :

```
var ampere = 0
var ampereRetour = 0
var onOrOff = false

while(ampere == 0) {
  var checkAmpere = function(console) {
    return console.ampere
  }

  var ampereRetour = checkAmpere();

  if(ampereRetour >= 15) {
    onOrOff = true
    console.log('La console est allumée.')
    ampere = ampereRetour
  } else if(ampereRetour == 0) {
      for(var i = 1; i <= 15; i++) {
        ampereRetour++
      }
      console.log('la console est allumée')
      ampere = ampereRetour
  }
}

```

### Exercice 3 : Faire le même exercice pour le panier de Gertrude
[En cours]

# Ce dont j'ai besoin et ce que je dois créer

- Les datas des produits de la carte
- Un id pour chaque produit de la carte
- Une variable pour stocker la qte de produits ajoutés
- Un bouton d'ajout au panier
- Un bouton supprimer du panier

# Ajouter au panier

```
1. Stocker en mémoire les boutons sous le nom btns
2. Réserver un espace mémoire pour quelque chose sous un nom de variable
...

```

# Supprimer du panier
