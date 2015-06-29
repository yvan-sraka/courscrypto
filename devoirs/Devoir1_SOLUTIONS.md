QUESTION 1
----------

1. DVJ HGIMJ JNBM MXVJ WUZBNBJ, JLXMNLM DVLXJ NXVUDDVJ

   Mot de trois lettres le plus courant en première position de phrase
   française : LES.  Tentons la subsitition D=L, V=E, J=S.
   Intuition : MXVJ est TRES, et donc DVLXJ est LEURS.
   À partir de là, JLXMNLM apparaît comme SURTOUT, NXVUDDVJ comme OREILLES
   puis JNBM comme SONT.
   Intuitivement, on a HGIMJ pour CHATS et WUZBNBJ pour MIGNONS.
   Le dictionnaire de mots croisés donne CHATS comme seule possibilité,
   et PIGNONS comme alternative dénuée de sens à MIGNONS.

   texte en clair : LES CHATS SONT TRES MIGNONS, SURTOUT LEURS OREILLES


2. Fonction de déchiffrement = décalage de 3 rangs en arrière (modulo 26)

   P  L  D  R  X   P  L  D  R  X   O  H  V   F  K  D  W  V   V  R  Q  W   
   16 12 04 18 24  16 12 04 18 24  15 08 22  06 20 04 23 22  22 18 17 23
   13 09 01 15 21  13 09 01 15 21  12 05 19  03 17 01 20 19  19 15 14 20
   M  I  A  O  U   M  I  A  O  U   L  E  S   C  H  A  T  S   S  O  N  T

   S  O  H  L  Q  V   G  H   F  D  O  L  Q  V
   19 15 08 12 17 22  07 08  06 04 15 12 17 22
   16 12 05 09 14 19  04 05  03 01 12 09 14 19
   P  L  E  I  N  S   D  E   C  A  L  I  N  S

   texte en clair : MIAOU MIAOU LES CHATS SONT PLEINS DE CALINS


QUESTION 2
----------
```
Pr(A) = 0.25  
Pr(B) = 0.55  
Pr(A ou B) <= Pr(A) + Pr(B)  
           <= 0.25  + 0.55  
           <= 0.80
```

Pr(A et B) = Pr(A) * Pr(B) = 0.25 * 0.55 = 0.1375


QUESTION 3
----------

1. U = {0,1}<sup>16</sup>
   card U = 2<sup>16</sup> = 65536

2. A = { LSB3(x) = 101 } ⊆ U
   En raisonnant par dichotomie : la moitié des séquences de U finissent par 1, 
   la moitié des séquences qui finissent par 1 finissent par 01, et la moitié des 
   séquences qui finissent par 01 finissent par 101 :
   card A = card U / 2 / 2 / 2  = 8192 = 2<sup>13</sup>
   Parce que la distribution des probabilités est uniforme sur U :
   Pr[A] = card A / card U = 2<sup>13</sup> / 2<sup>16</sup> = 1/8 = 0.125 = 12.5%


QUESTION 4
----------
```
    01011010
XOR 11010010
    --------
    10001000
```
