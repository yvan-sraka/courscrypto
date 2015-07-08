# Introduction à la Cryptographie
## Devoir 3: Chiffrement par Bloc

### Question 1
Considérez les cinq événements suivantes:

1. Deviner correctement une clé de 128 bits AES sur le premier essai.  
1. Gagner une loterie avec 1 million de participants (la probabilité est 1/10<sup>6</sup>).  
1. Gagner une loterie avec 1 million de participants 5 fois de suite (la probabilité est (1/10<sup>6</sup>)<sup>5</sup>).  
1. Gagner une loterie avec 1 million de participants 6 fois dans de suite.  
1. Gagner une loterie avec 1 million de participants 7 fois dans de suite.  

Quel est l'ordre de ces événements du plus probable au moins probable?

### Question 2
Supposons que il est possible de construire un ordinateur pour environ $200 qui peut essayer 1 milliard clés AES par seconde. Supposons qu'une organisation veut exécuter une recherche exhaustive pour une seule clé AES 128 bits et était prête à dépenser 4 trillions de dollars pour acheter ces machines (ce qui est plus que le budget annuel du gouvernement fédéral des États-Unis). Combien de temps faudrait-il à l'organisation de la force brutale de cette seule clé de 128 bits AES avec ces machines? Ignorez les frais supplémentaires tel que l'électricité.

### Question 3
Sachant que F:{0,1}<sup>n</sup> × {0,1}<sup>n</sup> → {0,1}<sup>n</sup> est une permutation pseudo-aléatoire sûre, lequel des permutations suivantes sont sûres aussi?
* G(k, x) = F(k, x) ⨁ F(k, x ⊕ 1<sup>n</sup>)
* G((k<sub>1</sub>, k<sub>2</sub>), x) = F(k<sub>1</sub>, x) ⨁ F(k<sub>2</sub>, x)
* G(k, x) = k ⨁ x
* G(k, x) = F(k, x)<sub>{0,…,n−2}</sub> (ce qui veut dire que G(k, x) laisse tomber le dernier bit de F(k, x))

### Question 4
Souvenez-vous que le théorème de Luby-Rackoff discuté dans cette session indique que l'application d'un réseau de Feistel de **trois** étapes à une fonction pseudo-aléatoire sûre donne chiffrement par bloc sur. Voyons ce qui va mal si nous utilisons un réseau Feistel avec seulement **deux** étapes. Soit F: K × {0,1}<sup>32</sup> → {0,1}<sup>32</sup> est une fonction pseudo-aléatoire sûre.

L'une des lignes suivantes est le output de ce réseau Feistel a deux étapes en utilisant une clé aléatoire, tandis que les trois autres sont la sortie d'un réseau Feistel avec plus que deux étapes. Pouvez-vous dire laquelle est l'output du réseau Feistel a deux étapes? Toutes les outputs sont codés comme 16 caractères hexadécimaux.

* Sur input 0<sup>64</sup>, le output est `7c2822eb fdc48bfb`. Sur input 1<sup>32</sup>0<sup>32</sup>, le output est `325032a9 c5e2364b`.
* Sur input 0<sup>64</sup>, le output est `9f970f4e 932330e4`. Sur input 1<sup>32</sup>0<sup>32</sup>, le output est `6068f0b1 b645c008`.
* Sur input 0<sup>64</sup>, le output est `5f67abaf 5210722b`. Sur input 1<sup>32</sup>0<sup>32</sup>, le output est `bbe033c0 0bc9330e`.
* Sur input 0<sup>64</sup>, le output est `7b50baab 07640c3d`. Sur input 1<sup>32</sup>0<sup>32</sup>, le output est `ac343a22 cea46d60`.

Astuce: Commencez par démontrer que il existe un pattern détectable dans F<sub>2</sub>(k, 0<sup>64</sup>) ⨁ F<sub>2</sub>(k, 1<sup>32</sup>0<sup>32</sup>).

Envoyez vos réponses a nadim@nadim.computer avant le Vendredi soir!

