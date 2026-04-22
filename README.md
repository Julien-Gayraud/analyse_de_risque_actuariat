# Titre du repository proposé

**modele_cramer_lundberg_actuariat**

---

# README.md

## 1. Contexte

Projet réalisé à **l’INSA Toulouse** dans le cadre du cursus de mathématiques appliquées, encadré par **Anthony Réveillac**.  

Le sujet porte sur l’étude probabiliste du modèle de **Cramér-Lundberg**, utilisé en actuariat pour modéliser le risque financier d’une compagnie d’assurance.

---
## 2. Présentation du projet

L’objectif du projet est d’étudier le **risque de ruine** ainsi que la **Value at Risk (VaR)** d’une compagnie d’assurance en fonction des paramètres du modèle de Cramér-Lundberg (capital initial, primes, intensité des sinistres, montant des sinistres, horizon temporel, etc.).

Le but est de comprendre l’impact de ces paramètres sur la solidité financière de l’assureur et sur son exposition aux pertes extrêmes.

Une ouverture du projet consiste à étudier une extension du modèle classique en introduisant un facteur d’actualisation des sinistres, afin de mieux représenter la valeur temporelle de l’argent et d’analyser son impact sur le risque.

---

## 3. Méthodes utilisées

Les simulations reposent sur :

- un **processus de Poisson homogène** pour modéliser l’arrivée aléatoire des sinistres ;
- des **variables aléatoires exponentielles** pour représenter le montant des sinistres ;
- des méthodes de **Monte-Carlo** pour estimer les probabilités de ruine et les indicateurs de risque comme la VaR.

L’ensemble du projet a été développé en **Python**, via un **Jupyter Notebook** contenant le code, les simulations et les résultats.
