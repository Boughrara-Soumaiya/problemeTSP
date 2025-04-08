#  IA – Algorithme Génétique pour le Problème du Voyageur de Commerce (TSP)

##  Présentation du projet

Ce projet implémente un **algorithme génétique** pour résoudre le **problème du voyageur de commerce** (TSP), un problème classique d’optimisation combinatoire.  
Il intègre une **interface graphique interactive** permettant de visualiser l’évolution des solutions et de suivre en temps réel le chemin optimal calculé.

L’objectif est de **minimiser la distance totale** parcourue en visitant une série de villes **une seule fois**, avant de revenir au point de départ, en s’appuyant sur des mécanismes inspirés de la sélection naturelle.


## Fonctionnalités

- Génération aléatoire de populations initiales
- Calcul des distances entre les villes (distance euclidienne)
- **Sélection par tournoi** pour choisir les individus les plus performants
- **Croisement PMX** (Partially Mapped Crossover) pour produire une nouvelle génération
- **Mutation par échange** pour introduire de la diversité
- **Visualisation cartographique** du parcours sur une carte mondiale avec **Cartopy**
- **Interface graphique avec PyQt6** pour interagir avec les paramètres de l’algorithme


## Technologies utilisées

Python 3.x, PyQt6, matplotlib et Cartopy 


## Prérequis

Assurez-vous d’avoir installé Python 3.x.  
Puis, installez les bibliothèques nécessaires avec la commande suivante :

<pre> pip install matplotlib PyQt6 cartopy  </pre>

## Créatrices 

Projet réalisé dans le cadre de la L3 en Intelligence Artificielle avec [MARIE-JOSEPH Emmy](https://github.com/emmy03).
