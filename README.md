# Projet : Modèle SEIR Multi-Agent  
## Simulation de la propagation d'une maladie sur une grille

**Date de rendu :** 07/04/2024 à 23h  
**Poids dans la note finale :** 40 %

---

## 1. Présentation générale

L’objectif de ce projet est de développer un **modèle multi-agent** simulant la **propagation d’une maladie infectieuse** dans une population.  
La simulation repose sur un modèle **SEIR** (Susceptible – Exposed – Infectious – Recovered) appliqué à une **grille 2D**, où chaque cellule représente un agent doté d’un état sanitaire.

Ce projet permet de se familiariser avec :

- la modélisation multi-agent ;
- les modèles épidémiologiques ;
- les règles d’interaction entre agents ;
- l’analyse et la visualisation de la propagation d’une maladie.

---

## 2. Objectifs pédagogiques

- Comprendre le fonctionnement du modèle **SEIR**.  
- Implémenter un système comportant :
  - une grille,
  - des agents,
  - des transitions d’état.
- Simuler et visualiser la propagation d’une maladie.
- Étudier l’impact de paramètres comme :
  - la probabilité d’infection,
  - la durée d’incubation,
  - la durée de contagiosité,
  - la taille de la population,
  - la densité de la grille.

---

## 3. Description du modèle SEIR

Chaque agent appartient à l’un des états suivants :

- **S – Susceptible :** agent sain mais infectable.  
- **E – Exposed :** agent contaminé mais non contagieux (phase d’incubation).  
- **I – Infectious :** agent contagieux pouvant transmettre la maladie.  
- **R – Recovered :** agent guéri et immunisé.


Chaque transition dépend de probabilités, durées ou règles que votre modèle devra gérer.

---

## 4. Environnement de simulation

La simulation se déroule dans une **grille 2D** où chaque cellule contient un agent.  
Les agents peuvent :

- interagir avec leurs voisins (voisinage de Moore ou de Von Neumann),
- changer d’état selon les règles du modèle SEIR,
- éventuellement se déplacer (si vous choisissez d’ajouter cette mécanique).

La simulation progresse en **pas de temps (ticks)**.

---

## 5. Travail à réaliser

### A. Modélisation et Implémentation
- Représentation de la grille.
- Représentation des agents et de leurs états.
- Gestion des transitions SEIR :
  - incubation (S → E),
  - contagion (E → I),
  - guérison (I → R).
- Paramètres configurables :
  - taille de la grille,
  - population initiale,
  - nombre initial de malades,
  - durées des phases SEIR,
  - probabilité d’infection.

### B. Visualisation
La simulation doit inclure :

- une représentation visuelle ou graphique de la grille,
- des courbes montrant l’évolution des populations S, E, I et R au cours du temps.

---

## 6. Contraintes

- **Date limite :** 07/04/2024 à 23h.  
- **Coefficient :** 40 % de la note finale.  
- **Travail en groupe.**

---

## 7. Membres du groupe

- **Jacques KOZIK**  
- **Killian GALFRE–VEYRET**  
- **Arij HADDA**

---



 
