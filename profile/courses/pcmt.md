# Programmation Concurrente en Multi-Threads

Cette page présente le cours **Programmation Concurrente en Multi-Threads**, enseigné à Nantes Université, ainsi que les ressources pédagogiques qui lui sont associées.

## Ressources du module

### Cours magistral

* [Diaporama](https://DistributedComputing.github.io/CM/pcmt/cours.pdf) : version PDF avec animations
* [Version sans animations](https://DistributedComputing.github.io/CM/pcmt/handout/cours.pdf) : version PDF destinée à la consultation ou à l’impression
* [Exemples Java](https://github.com/DistributedComputing/Exemples-Java) : exemples utilisés dans le cours

### Travaux dirigés

* [Livret de TD](https://DistributedComputing.github.io/TD/pcmt/td.pdf) : livret de travaux dirigés

### Travaux pratiques

* **TP 1 — Introduction à la concurrence**
  * [Sujet](https://DistributedComputing.github.io/TD/pcmt/tp-concurrence.pdf) : version PDF du sujet
  * [Code Java](https://github.com/DistributedComputing/TP-concurrence) : code à étudier

* **TP 2 — Recherche récursive d’expressions régulières sur le Web**
  * [Sujet](https://DistributedComputing.github.io/TD/pcmt/tp-webgrep.pdf) : version PDF du sujet
  * [Code Java](https://github.com/DistributedComputing/TP-webgrep) : code séquentiel à paralléliser

* **TP 3 — Parallélisation de calcul d’image**
  * [Sujet](https://DistributedComputing.github.io/TD/pcmt/tp-mandelbrot.pdf) : version PDF du sujet
  * [Code Java](https://github.com/DistributedComputing/TP-mandelbrot) : code séquentiel à paralléliser

* **TP 4 — Mémoire transactionnelle logicielle**
  * [Sujet](https://DistributedComputing.github.io/TD/pcmt/tp-transactions.pdf) : version PDF du sujet
  * [Code Java](https://github.com/DistributedComputing/TP-transactions) : code à compléter

## Description du module

Ce cours est destiné aux étudiants de M1 informatique, ainsi qu’à toute personne s’intéressant à la programmation concurrente et à la synchronisation en mémoire partagée.

Le responsable du module est Matthieu Perrin.

Les volumes horaires consacrés à ce cours à Nantes Université, pour des séances de 1 h 20, sont les suivants :

| Activité          | Volume |
| ----------------- | -----: |
| Cours magistraux  |   12 h |
| Travaux dirigés   | 6 h 40 |
| Travaux pratiques | 5 h 20 |

### Contenu

* Introduction à la concurrence
  * nature des problèmes dans les systèmes à mémoire partagée
  * modèles d’exécution concurrente
  * limites et précautions dans l’usage des threads
* Techniques de synchronisation bloquante
  * verrous
  * moniteurs
  * problèmes de vivacité : interblocage et famine
* Implémentation et modèle mémoire
  * algorithmes de verrous de Peterson et de Lamport
  * modèle mémoire et gestion de la volatilité

### Résultats d’apprentissage

À la fin de ce cours, un étudiant doit être capable de :

* Identifier les possibilités de parallélisation d’un programme.
* Raisonner sur la concurrence et identifier les problèmes d’exécution concurrente.
* Proposer des solutions bloquantes aux problèmes de concurrence.
* Concevoir et implémenter des mécanismes de synchronisation sûrs.
* Développer des applications multi-threads robustes.
* Lire et comprendre la documentation officielle des bibliothèques de gestion de la concurrence.

### Bibliographie

* M. Herlihy et N. Shavit. **The Art of Multiprocessor Programming**, Morgan Kaufmann, 2008.
  > Référence principale sur la programmation concurrente en Java.

* M. Raynal. **Concurrent Programming – Algorithms, Principles, and Foundations**, Springer, 2013.
  > Référence pour les aspects plus algorithmiques du module.
