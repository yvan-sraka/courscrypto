# Introduction a la Cryptographie
**Chaque Samedi a 12h00, au Loop (20 rue de Reuilly, 75012 Paris)**

Ce cours est une introduction à la théorie de base et la pratique de techniques cryptographiques utilisées dans la sécurité informatique. Nous allons couvrir des sujets tels que le cryptage (clé secrète et à clé publique), l'intégrité des messages, signatures numériques, l'authentification des utilisateurs, la gestion des clés, hachage cryptographique, protocoles de sécurité de réseau (SSL, IPSec), l'infrastructure à clé publique, la gestion des droits numériques, et un peu de sujets plus avancés.

**Livre gratuit contenant du matériel utile en Anglais**: [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/)

### Lecture 1: Histoire de la cryptographie
**20 Juin 2015**  

Reading: HAC 11-20.

## Chiffrement Symmetrique
 
### Lecture 2: Chiffrement de Flux
**27 Juin 2015**
* Le "one time pad".
* La securité semantique.  

Reading: HAC 20-21, 191-194.
 
### Lecture 3: Chiffrement par Bloc
**4 Juillet 2015**
* Etude de cas: Reseaux Feistel, DES, 3DES et AES.
* Modes d'operation: CBC et mode de compteur.  

Reading: HAC 233-237, 250-259
 
### Lecture 4: Abstractions du Chiffrement par Bloc
**11 Juillet 2015**
* Permutations pseudo-aléatoires.
* Fonctions pseudo-aléatoires.
* Securité contre les attaques du clair choisi (CPA).
* Chiffrement CBC basé sur les nonces et mode de compteur.  

Reading: HAC 228-230
 
### Lecture 5: Cryptanalyse Differentiele et Linéare
**18 Juillet 2015**
* Recherche exhaustif, compromis temps-espace.
* Attaque "meet in the middle".
* Attaques sur le canal latéral.

## Integrité Cryptographique
 
### Lecture 6: Integrité Cryptographique
**25 Juillet 2015**
* Integrité des messages: definitions et applications.
* CBC-MAC et PMAC.
 
### Lecture 7: Hachage Cryptographique
**1 Aout 2015**
* Hachage resistant aux collisions.
* Merkle-Damgard et Davies-Meyer. MACs basés sur la resistance aux collisions.
* Etudes de cas: SHA et HMAC (possiblement MD5).  

Reading: HAC 333-335, 339-341, 348
 
### Lecture 8: Chiffrement Authentifié
**8 Aout 2015**
* Securité contre l'attaquant actif vs. attaquant passif.

## Chiffrement Asymmetrique
 
### Lecture 9: Arithmetique Modulaire sur Nombres Premiers
**15 Aout 2015**

### Lecture 10: Cryptographie en Arithmetique Modulaire
**22 Aout 2015**
* Arithmetique modulaire et nombres premiers.
* Protocole Diffie-Hellman.
* Hypothèse de calcul Diffie-Hellman.
* Hypothèse décisionnel Diffie-Hellman.
 
### Lecture 11: Chiffrement à clé publique
**29 Aout 2015**
* Protocole ElGamal.
* Notion de securité CCA ("Chosen Ciphertext Attack")
 
### Lecture 12: RSA
**5 Septembre 2015**
* Arithmetique modulo composites.
* Fonctions RSA et Rabin.
* Permutations "trapdoor".

## Signatures Cryptographiques
 
### Lecture 13: Signatures Cryptographiques: Definitions et Applications
**12 Septembre 2015**
* Signatures avec RSA.

### Lecture 14: Autres Schemas de Signature
**19 Septembre 2015**
* Schemas de Lamport and Merkle.
* Certificats et gestion de la confiance.

## Sujets Finaux
 
### Lecture 15: Protocoles d'Identification
**26 Septembre 2015**
* Protocoles de mots de passe.
* Protocoles "one time password".
* Authentification "challenge-response".  

Reading: HAC Chapitre 10.
 
### Lecture 16: Échange de clés authentifié
**3 Octobre 2015**
* Initialization de sessions TLS/SSL.
 
### Lecture 17: Protocoles Zero-Knowledge
**10 Octobre 2015**

### Lecture 18: Sujets Avancés
**17 Octobre 2015**
