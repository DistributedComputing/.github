# Distributed Computing

Cette organisation contient les ressources et projets liés au cours **Services de Communication et Systèmes Distribués** de Nantes Université.

## Description du module

Ce cours est destiné à des étudiants de M2 en Informatique, ainsi qu'à toute personne s'intéressant à la synchronisation des systèmes répartis.

Le responsable du module est Matthieu Perrin.

Les volumes horaires dédiés à ce cours à Nantes Université (séances de 1h20) sont les suivants :
- Cours magistraux : 12h
- Travaux dirigés : 12h

### Contenu
- Modèles de systèmes répartis
  - processus asynchrone
  - hypothèses sur la communication
  - tolérance aux fautes
- Structures de données répliquées
​  - protocoles de réplication
  - machine à états répliquée
  - cohérence des données partagées
- Algorithmes répartis
  - abstractions de diffusion : diffusion fiable, FIFO, causale
  - simulation d'un registre atomique répliqué
  - consensus et diffusion totalement ordonnée

### Résultats d'apprentissage
À la fin de ce cours, un étudiant doit être capable de :
- Identifier et expliciter les hypothèses nécessaires au fonctionnement d’un algorithme réparti.
- Analyser les garanties et les limites des principales abstractions réparties étudiées.
- Évaluer la conformité d’une exécution à un critère de cohérence.
- Construire des exécutions d’un algorithme réparti donné ne respectant pas certaines propriétés.
- Justifier la correction d’un algorithme réparti.

### Bibliographie
- M. Raynal. **Fault-Tolerant Message-Passing Distributed Systems: An Algorithmic Approach**, Springer, 2018.

## Dépôts principaux
- [**CM**](https://github.com/DistributedComputing/CM) — Slides de cours.
  - [Slides](https://DistributedComputing.github.io/CM/slides.pdf): version PDF avec animations
  - [Handout](https://DistributedComputing.github.io/CM/handout.pdf): version PDF sans animation
- [**TD**](https://github.com/DistributedComputing/TD) — Énoncés et corrections de TD.
  - Dépôt privé accessible aux enseignants sur demande

## Cours liés
Ce cours a été conçus comme la deuxième partie sur trois d'un cours sur la synchronisation des systèmes répartis : 
- [**Programmation Concurrente en Multi-Thread**](https://github.com/ProgrammationMultiThread/CM) — Programmation multi-threads bloquante en mémoire partagée.
- [**Programmation Distribuée**](https://github.com/AlgorithmiqueConcurrente/CM) — Algorithmique concurrente non-bloquante en mémoire partagée.
- [**Services de Communication et Systèmes Distribués**](https://github.com/DistributedComputing/CM) — Algorithmique tolérante aux pannes en passage de messages.

## Licence
Sauf mention contraire, les contenus sont sous licence
- [Creative Commons Attribution - ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) pour les sources LaTeX.
