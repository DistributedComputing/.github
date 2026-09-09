# Algorithmique des Structures de Données Concurrentes

Cette page présente le cours **Programmation Distribuée**, enseigné à Nantes Université, ainsi que les ressources pédagogiques qui lui sont associées.

## Ressources du module

### Cours magistral

* [Diaporama](https://DistributedComputing.github.io/CM/pdac/cours.pdf) : version PDF avec animations
* [Version sans animations](https://DistributedComputing.github.io/CM/pdac/handout/cours.pdf) : version PDF destinée à la consultation ou à l’impression
* [Exemples Java](https://github.com/DistributedComputing/Exemples-Java) : exemples utilisés dans le cours

### Travaux dirigés

* [Livret de TD](https://DistributedComputing.github.io/TD/pdac/td.pdf) : livret de travaux dirigés

## Description du module

Ce cours est destiné aux étudiants de M1 informatique, ainsi qu’à toute personne s’intéressant à l’algorithmique concurrente et à la synchronisation en mémoire partagée.

Le responsable du module est Matthieu Perrin.

Les volumes horaires consacrés à ce cours à Nantes Université, pour des séances de 1 h 20, sont les suivants :

| Activité         | Volume |
| ---------------- | -----: |
| Cours magistraux |   12 h |
| Travaux dirigés  |   12 h |

### Contenu

* Modèles et primitives de synchronisation
  * asynchronisme et pannes
  * instructions atomiques
* Conception et analyse de structures non bloquantes
  * conditions de progression : *lock-freedom* et *wait-freedom*
  * algorithmes de structures de données non bloquantes : piles, files et compteurs
* Résultats fondamentaux
  * impossibilité du consensus
  * hiérarchie de Herlihy

### Résultats d’apprentissage

À la fin de ce cours, un étudiant doit être capable de :

* Identifier la condition de progression d’un algorithme concurrent donné.
* Concevoir une structure de données non bloquante simple en respectant les principes de progression.
* Identifier et expliciter les hypothèses nécessaires à la conception d’une structure de données concurrente.
* Mettre en œuvre un algorithme de structure de données non bloquante dans un langage de programmation orienté objet.

### Bibliographie

* M. Raynal. **Concurrent Programming – Algorithms, Principles, and Foundations**, Springer, 2013.
