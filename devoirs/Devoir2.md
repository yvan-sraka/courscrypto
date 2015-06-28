# Introduction à la Cryptographie
## Devoir 2: Chiffrement de Flux

### Question 1
La compression des données est souvent utilisée dans le stockage de données et la transmission. Supposons que vous voulez utiliser la compression de données avec un chiffrement de flux. Est-il plus judicieux de chiffrer les données avant la compression, ou après? Justifiez votre réponse.

### Question 2
Sachant que G:{0,1}<sup>s</sup>→{0,1}<sup>n</sup> est une fonction pseudo-aléatoire sûre, lequel des fonctions H suivants est une fonction pseudo-aléatore sûre aussi? (il y'a plus q'une réponse correcte):
* H(k) = G(k) + 0  
* H(k) = G(k) + G(k)  
* H(k) = G(k) ⨁ 1<sup>n</sup>
* H(k) = G(0)
* H(k) = G(k⊕1<sup>s</sup>)

### Question 3
(E, D) est un chiffrement sémantiquement sûr avec l'espace de clés K = {0,1}<sup>n</sup>. Une banque souhaite diviser une clé k en deux pièces P1 et P2 de sorte que les deux sont nécessaires pour le déchiffrement. P<sub>1</sub> peut être accordée à une personne et P<sub>2</sub> à un autre de telle sorte que les deux doivent apporter leurs pièces pour procéder avec le déchiffrement.

Pour accomplir cette tache, la banque génère un k<sub>1</sub> aléatoire dans {0,1}<sup>n<sup> et définit k'<sub>1</sub> ← k⊕k<sub>1</sub>. Notez que k<sub>1</sub>⊕k'<sub>1</sub> = k. La banque peut donner k<sub>1</sub> à une personne et k'<sub>1</sub> à l'autre. Les deux doivent être présents pour le déchiffrement puisque, par elle-même, chaque pièce contient aucune information sur la clé secrète k.

Maintenant, supposons que la banque veut diviser k en trois morceaux P<sub>1</sub>, P<sub>2</sub>, P<sub>3</sub> de sorte que tout **deux** des trois pièces permettent le déchiffrement en utilisant k. Cela garantit que même si une des personne est en congé, le déchiffrement peut encore réussir. La banque génère deux paires aléatoires (k<sub>1</sub>, k'<sub>1</sub>) et (k<sub>2</sub>, k'<sub>2</sub>), de sorte que k<sub>1</sub>⊕k'<sub>1</sub> = k<sub>2</sub>⊕k'<sub>2</sub> = k. Comment doit la banque céder ces morceaux de sorte que deux personnes peuvent déchiffrer en utilisant k, mais que une seule personne ne peut jamais déchiffrer toute seule?

Envoyez vos réponses a nadim@nadim.computer avant le Vendredi soir!

