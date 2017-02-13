# Les algo c'est beau

### Exercice 1 : La machine à qui vous donner des ordres :

## Je veux que la machine
Allume la console

## Ma machine possède
- Une mémoire (par défaut)
- Une camera
- Des ports pour connecter l'ordinateur à la console
- Un écran
- multimetre

## Ordres

```
Connecter l'ordinateur à la console
On estime que la console est allumée si les ampères dépassent 15

1. Écrire 0 dans une variable : amperes
2. Réserver un espace mémoire pour stocker un booléen qui stocke l'information (si la console est allumée ou pas) sous le nom : onOrOff
3. Écrire en mémoire que onOrOff est false
4. Calculer les ampères de la console
5. Stocker les ampères dans ampères
5. Si ampère supérieur ou égal à 15 changer la valeur de onOrOff en true
6. Afficher 'La console est allumée'

```

### Exercice 2 : L'ordinateur à qui vous donner des ordres :

```

var amperes = 0
var onOrOff = false

var amperes = multimetre.getAmp(console)
if (amperes >= 15) { onOrOff = true }
console.log('La console est allumée')
else { console.log('La console est éteinte')}

```
