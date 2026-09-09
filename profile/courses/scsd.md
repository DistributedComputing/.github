# Services de Communication et Systèmes Distribués

Cette page présente le cours **Services de Communication et Systèmes Distribués**, enseigné à Nantes Université, ainsi que les ressources pédagogiques qui lui sont associées.

## Ressources du module

### Cours magistral

* [Diaporama](https://DistributedComputing.github.io/CM/scsd/cours.pdf) : version PDF avec animations
* [Version sans animations](https://DistributedComputing.github.io/CM/scsd/handout/cours.pdf) : version PDF destinée à la consultation ou à l’impression

### Travaux dirigés

* [Livret de TD](https://DistributedComputing.github.io/TD/scsd/td.pdf) : livret de travaux dirigés

## Description du module

Ce cours est destiné aux étudiants de M2 informatique, ainsi qu’à toute personne s’intéressant à la synchronisation des systèmes répartis.

Le responsable du module est Matthieu Perrin.

Les volumes horaires consacrés à ce cours à Nantes Université, pour des séances de 1 h 20, sont les suivants :

| Activité         | Volume |
| ---------------- | -----: |
| Cours magistraux |   12 h |
| Travaux dirigés  |   12 h |

### Contenu

* Modèles de systèmes répartis
  * processus asynchrones
  * hypothèses sur la communication
  * tolérance aux fautes
* Structures de données répliquées
  * protocoles de réplication
  * machines à états répliquées
  * cohérence des données partagées
* Algorithmes répartis
  * abstractions de diffusion : diffusion fiable, FIFO et causale
  * simulation d’un registre atomique répliqué
  * consensus et diffusion totalement ordonnée

### Résultats d’apprentissage

À la fin de ce cours, un étudiant doit être capable de :

* Identifier et expliciter les hypothèses nécessaires au fonctionnement d’un algorithme réparti.
* Analyser les garanties et les limites des principales abstractions réparties étudiées.
* Évaluer la conformité d’une exécution à un critère de cohérence.
* Construire des exécutions d’un algorithme réparti donné violant certaines propriétés.
* Justifier la correction d’un algorithme réparti.

### Bibliographie

* M. Raynal. **Distributed Algorithms for Message-Passing Systems**, Springer, 2013.
  > Référence principale sur les modèles à passage de messages.

* M. Raynal. **Fault-Tolerant Message-Passing Distributed Systems: An Algorithmic Approach**, Springer, 2018.
  > Référence principale sur les algorithmes liés à la tolérance aux fautes.

* M. Perrin. **Distributed Systems: Concurrency and Consistency**, ISTE Press et Elsevier, 2017.
  > Introduction plus synthétique aux modèles de cohérence et de synchronisation.
