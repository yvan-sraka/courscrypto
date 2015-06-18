# Introduction a la Cryptographie
**Chaque Samedi a 12h00, au Loop (20 rue de Reuilly, 75012 Paris)**

:key::key::key::key::key::key::key::key::key::key::key::key::key::key:

Ce cours est une introduction à la théorie de base et la pratique de techniques cryptographiques utilisées dans la sécurité informatique. Nous allons couvrir des sujets tels que le chiffrement (clé secrète et à clé publique), l'intégrité des messages, signatures numériques, l'authentification des utilisateurs, la gestion des clés, hachage cryptographique, protocoles de sécurité de réseau (SSL, IPSec), l'infrastructure à clé publique, la gestion des droits numériques, et un peu de sujets plus avancés.

:apple: :grapes: :cherries: Miam-miam gratuit a chaque session pour tout le monde qui participe! :apple: :grapes: :cherries:

**Livre gratuit contenant du matériel utile en Anglais**: [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/)

## Partie 0: Culture

### Session 1: Histoire de la cryptographie
**20 Juin 2015**  

Reading: HAC 11-20.

## Partie 1: Chiffrement Symétrique
 
### Session 2: Chiffrement de Flux
**27 Juin 2015**
* Le "one time pad".
* La sécurité sémantique.  

Reading: HAC 20-21, 191-194.
 
### Session 3: Chiffrement par Bloc
**4 Juillet 2015**
* Etude de cas: Réseaux Feistel, DES, 3DES et AES.
* Modes d'operation: CBC et mode de compteur.  

Reading: HAC 233-237, 250-259
 
### Session 4: Abstractions du Chiffrement par Bloc
**11 Juillet 2015**
* Permutations pseudo-aléatoires.
* Fonctions pseudo-aléatoires.
* Sécurité contre les attaques du clair choisi (CPA).
* Chiffrement CBC basé sur les nonces et mode de compteur.  

Reading: HAC 228-230
 
### Session 5: Cryptanalyse Différentielle et Linéaire
**18 Juillet 2015**
* Recherche exhaustif, compromis temps-espace.
* Attaque "meet in the middle".
* Attaques sur les "side channels" (canaux latéraux).

## Intégrité Cryptographique
 
### Session 6: Intégrité Cryptographique
**25 Juillet 2015**
* Intégrité des messages: definitions et applications.
* CBC-MAC et PMAC.
 
### Session 7: Hachage Cryptographique
**1 Aout 2015**
* Hachage resistant aux collisions.
* Protocoles Merkle-Damgard et Davies-Meyer.
* MACs basés sur la resistance aux collisions.
* Etudes de cas: SHA et HMAC (possiblement MD5).  

Reading: HAC 333-335, 339-341, 348
 
### Session 8: Chiffrement Authentifié
**8 Aout 2015**
* Sécurité contre l'attaquant actif vs. attaquant passif.

## Partie 2: Chiffrement Asymétrique
 
### Session 9: Arithmétique Modulaire sur Nombres Premiers
**15 Aout 2015**

### Session 10: Cryptographie en Arithmétique Modulaire
**22 Aout 2015**
* Arithmétique modulaire et nombres premiers.
* Protocole Diffie-Hellman.
* Hypothèse de calcul Diffie-Hellman.
* Hypothèse décisionnel Diffie-Hellman.
 
### Session 11: Chiffrement à clé publique
**29 Aout 2015**
* Protocole ElGamal.
* Notion de sécurité CCA ("Chosen Ciphertext Attack")
 
### Session 12: RSA
**5 Septembre 2015**
* Arithmétique modulo composites.
* Fonctions RSA et Rabin.
* Permutations "trapdoor".

## Partie 3: Signatures Cryptographiques
 
### Session 13: Signatures Cryptographiques: Definitions et Applications
**12 Septembre 2015**
* Signatures avec RSA.

### Session 14: Autres Schemas de Signature
**19 Septembre 2015**
* Schemas de Lamport and Merkle.
* Certificats et gestion de la confiance.

## Partie 4: Sujets Finaux
 
### Session 15: Protocoles d'Identification
**26 Septembre 2015**
* Protocoles de mots de passe.
* Protocoles "one time password".
* Authentification "challenge-response".  

Reading: HAC Chapitre 10.
 
### Session 16: Échange de clés authentifié
**3 Octobre 2015**
* Initialisation de sessions TLS/SSL.
 
### Session 17: Protocoles Zero-Knowledge
**10 Octobre 2015**

### Session 18: Sujets Avancés
**17 Octobre 2015**
* Proposez vos propres sujets pour discuter!

