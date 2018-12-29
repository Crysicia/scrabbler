# Scrabble

## Setup

1. Fork et clone ce repo (N'oublie pas de clone TON fork).
2. Exécute `bundle install`.
3. Exécute `rspec`.

Cela va lancer plusieurs tests sur le fichier `lib/scrabble_word.rb`. La première fois que tu exécutes `rspec` tous les tests vont échouer parce qu'il n'y a pas encore de code dans `lib/scrabble_word.rb`.

Tu vas devoir ajouter du code dans `lib/scrabble_word.rb` de manière à ce que tous les tests passent. À moins de vouloir faire l'exercice bonus, **tu n'auras qu'à modifier `lib/scrabble_word.rb`**.

Si tu n'as jamais joué au Scrabble, demande à ton voisin de t'expliquer les règles :).

## Specs

* Définis une classe ScrabbleWord avec une méthode `initialize` qui prend un argument (`word`) et qui le stocke dans une variable d'instance `@word`.

* Écris un "getter" qui renvoie `@word`en basse-casse.

* Définis une méthode `score` qui renvoie la valeur en point du mot.

* Définis une méthode `multiplier_score` qui prend un multiplicateur en argument et renvoie le score multiplié. (Pense au mot compte double et triple.)

Voici la valeur des lettres. Réfléchis à comment tu pourrais mettre ces données dans un format utilisable.


```
a: 1, b: 3, c: 3, d: 2, e: 1,
f: 4, g: 2, h: 4, i: 1, j: 8,
k: 5, l: 1, m: 3, n: 1, o: 1,
p: 3, q: 10, r: 1, s: 1, t: 1,
u: 1, v: 4, w: 4, x: 8, y: 4,
z: 10
```
