# FCSC 2025 Bigorneau

On cherche souvent à obtenir des shellcodes avec des contraintes bizarres, soit en taille, soit alphanumérique, etc. Ici, on tente une nouvelle contrainte bizarre pour un shellcode x64 : vous n’avez le droit d’utiliser que 6 valeurs d’octets différents (i.e., `len(set(shellcode)) <= 6`) !

Auteurs : Cryptanalyse et XeR

Origine : [Bigorneau](https://hackropole.fr/fr/challenges/pwn/fcsc2025-pwn-bigorneau/)


## Challenge
[files/bigorneau](files/bigorneau)
[files/bigorneau.c](files/bigorneau.c)
[files/bigorneau.py](files/bigorneau.py)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-pwn-bigorneau.git

> cd fcsc2025-pwn-bigorneau

> docker compose up

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2025-pwn-bigorneau/
