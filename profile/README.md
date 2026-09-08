# Services de Communication et Systèmes Distribués

Cette organisation regroupe les ressources pédagogiques du cours **Services de Communication et Systèmes Distribués** à Nantes Université.

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

## Cours liés

Ce cours constitue le dernier volet d’un ensemble de trois cours consacrés à la synchronisation des systèmes répartis :

* [**Programmation Concurrente en Multi-Threads**](https://github.com/ProgrammationMultiThread) — Programmation multi-threads bloquante en mémoire partagée.
* [**Programmation Distribuée**](https://github.com/AlgorithmiqueConcurrente) — Algorithmique concurrente non bloquante en mémoire partagée.
* [**Services de Communication et Systèmes Distribués**](https://github.com/DistributedComputing) — Algorithmique tolérante aux pannes dans les systèmes à passage de messages.

## Licence

Sauf mention contraire dans le dépôt concerné, les contenus originaux de cette organisation sont distribués sous la licence [Creative Commons Attribution – Partage dans les mêmes conditions 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

Certains contenus, notamment les sujets d’évaluation non publiés, peuvent être soumis à des conditions plus restrictives précisées dans leur dépôt.

Les conditions détaillées, les mentions d’attribution ainsi que les licences des images et des données externes sont indiquées dans le fichier [`LICENSE.md`](https://github.com/DistributedComputing/.github/blob/main/LICENSE.md).
