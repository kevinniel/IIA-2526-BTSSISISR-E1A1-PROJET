# TP Fil Rouge — Gestion de projet SISR

# WBS, PERT et Gantt — Déploiement d’une infrastructure réseau

## Groupes

Groupe 1 : 
- Mathis
- Gabin

Groupe 2 : 
- Grégoire
- Elias

Groupe 3 : 
- Jean Claude
- Aurele

Groupe 4 : 
- Zoé
- Lucas

groupe 5 :
- Tigane
- Mael
- Alban

groupe 6 :
- Thomas
- Léo

groupe 7 :
- Jonathan
- Ludivine

groupe 8 :
- Mathéo
- Florian
- Mathias

---

# Contexte global

Vous travaillez dans une entreprise de services numériques spécialisée en infrastructure réseau.

Un client souhaite installer l’infrastructure réseau d’une petite entreprise de 25 salariés répartis dans plusieurs services :

* Direction
* Administration
* Commercial
* Technique
* Invités

L’entreprise souhaite disposer d’un réseau fiable, structuré et sécurisé permettant :

* l’accès à Internet
* la séparation des services par VLAN
* l’attribution automatique des adresses IP
* le partage de fichiers
* une connexion Wi-Fi pour les collaborateurs
* un réseau Wi-Fi invité isolé
* une sécurité réseau minimale
* une documentation claire de l’installation

Votre mission consiste à structurer, planifier et organiser ce projet afin de le rendre réalisable.

L’objectif est de livrer une **infrastructure réseau fonctionnelle rapidement**, sous forme de MVP, afin que l’entreprise puisse commencer à travailler dans de bonnes conditions.

Vous allez construire progressivement :

* un WBS — Work Breakdown Structure
* un diagramme PERT
* un diagramme de Gantt

---

# 1 — Construction d’un WBS

## Description du projet

L’infrastructure devra permettre :

* de connecter les postes utilisateurs au réseau local
* de séparer les services avec des VLAN
* de définir un plan d’adressage IP cohérent
* de configurer un serveur DHCP
* de configurer un accès Internet via un routeur ou pare-feu
* de mettre en place un partage de fichiers simple
* de créer un réseau Wi-Fi interne
* de créer un réseau Wi-Fi invité isolé
* de sécuriser les accès réseau de base
* de tester la connectivité entre les équipements
* de produire une documentation technique claire

---

## Contraintes projet

* délai maximum : 30 jours
* équipe :

  * 2 techniciens réseau
  * 1 administrateur système
  * 1 chef de projet
* budget limité : certaines fonctionnalités pourront être simplifiées
* objectif : livrer une infrastructure testable et utilisable rapidement

---

## Étape 1 — Construction initiale

Construire un WBS en respectant les règles suivantes :

* minimum 3 niveaux de profondeur
* maximum 10 grandes phases au niveau 1
* minimum 15 tâches au total
* chaque tâche doit être :

  * claire
  * actionnable
  * mesurable

## Étape 2 — Structuration obligatoire

Votre WBS doit obligatoirement contenir des éléments liés à :

* analyse du besoin réseau
* architecture réseau
* adressage IP
* VLAN
* routage
* DHCP
* Wi-Fi
* sécurité réseau
* tests de connectivité
* documentation technique
* déploiement

## Étape 3 — Analyse MVP

Identifier dans votre WBS :

* les tâches indispensables au MVP
* les tâches secondaires à prévoir plus tard

Vous devez distinguer clairement ces deux catégories.

## Étape 4 — Ajustement après nouvelle contrainte

Nouveau contexte :

Le client réduit le budget.

Vous devez :

* supprimer ou simplifier certaines fonctionnalités
* adapter votre WBS en conséquence
* conserver une infrastructure cohérente et testable


## Livrables attendus

Vous devez rendre :

* un WBS complet avec 3 niveaux minimum
* une distinction claire entre :

  * tâches MVP
  * tâches secondaires
* une version optimisée du WBS après réduction du budget

> Note : Vous avez donc 2 WBS à rendre pour cette étape !!!

# 2 — WBS + PERT

## Objectifs

* Identifier les dépendances entre les tâches
* Construire un diagramme PERT
* Comprendre l’ordre logique de réalisation d’un projet réseau

---

## Brief

Le client souhaite maintenant planifier le projet.

Certaines tâches ne peuvent démarrer que lorsque d’autres sont terminées.

Exemples :

* on ne peut pas configurer les VLAN avant d’avoir défini l’architecture réseau
* on ne peut pas tester le DHCP avant de l’avoir configuré
* on ne peut pas valider l’accès Internet avant d’avoir configuré le routeur
* on ne peut pas déployer définitivement sans tests validés

## Consignes

À partir de votre WBS :

1. sélectionner les tâches principales du projet
2. identifier les dépendances entre les tâches
3. construire un diagramme PERT
4. utiliser uniquement des dépendances logiques de type fin → début

## Contraintes

* minimum 8 tâches dans le PERT
* aucune boucle autorisée
* chaque tâche doit avoir au moins une dépendance, sauf la tâche de début
* chaque tâche doit être clairement nommée
* les dépendances doivent être justifiées

## Livrables

Vous devez rendre :

* un WBS adapté si nécessaire
* la liste des dépendances
* un diagramme PERT clair avec :

  * tâches identifiées
  * dépendances visibles

# 3 — PERT, chemin critique et Gantt

## Objectifs

* Calculer la durée totale du projet
* Identifier les tâches critiques
* Construire un diagramme de Gantt
* Comprendre l’impact d’un retard sur le projet

## Brief

Le client souhaite connaître :

* la durée totale du projet
* les tâches critiques
* les tâches pouvant avoir du retard sans bloquer tout le projet
* un planning clair

## Consignes

À partir du PERT :

1. intégrer les durées dans le diagramme
2. calculer les dates au plus tôt
3. calculer les dates au plus tard
4. identifier les marges
5. identifier le chemin critique
6. construire un diagramme de Gantt


## Calculs attendus

Pour chaque tâche, vous devez indiquer :

| Élément           | Signification                                                                |
| ----------------- | ---------------------------------------------------------------------------- |
| Date au plus tôt  | date à laquelle la tâche peut commencer au plus tôt                          |
| Date au plus tard | date à laquelle la tâche peut commencer au plus tard sans retarder le projet |
| Marge             | retard possible sans impact sur la durée totale                              |
| Tâche critique    | tâche avec une marge égale à 0                                               |


## Livrables

Vous devez rendre :

* un diagramme PERT avec les durées
* un tableau des calculs :

  * dates au plus tôt
  * dates au plus tard
  * marges
* le chemin critique identifié
* un diagramme de Gantt finalisé

# Critères d’évaluation

| Critère           | Attendu                                                    |
| ----------------- | ---------------------------------------------------------- |
| WBS               | Structure claire, 3 niveaux minimum, tâches mesurables     |
| MVP               | Distinction claire entre indispensable et secondaire       |
| Adaptation budget | Simplification cohérente du projet                         |
| PERT              | Dépendances logiques, aucune boucle                        |
| Calculs           | Dates au plus tôt, dates au plus tard et marges cohérentes |
| Chemin critique   | Correctement identifié                                     |
| Gantt             | Planning lisible et cohérent                               |
| Qualité globale   | Travail propre, structuré et compréhensible                |


# Résultat attendu

À la fin du TP, vous devez être capable de transformer un besoin client en projet structuré, planifié et réaliste.

Vous devez montrer que vous savez :

* découper un projet réseau
* identifier les tâches importantes
* distinguer le MVP des améliorations futures
* organiser les dépendances entre tâches
* calculer un chemin critique
* construire un planning projet

# Rendu final

Le rendu final est attendu pour le Vendredi 5 Juin à 17h **maximum** par mail, à l'adresse : k.niel.pro@gmail.com 
Merci de mettre en objet du mail : "IIA SISR TP Projet - Groupe X" en mettant votre bon numéro de groupe !
