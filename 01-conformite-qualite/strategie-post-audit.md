---
id: prompt-09
title: Générer une stratégie post-audit DREETS ou Qualiopi
category: conformite-qualite
status: optimise
source: guide-ia-pratique
tags:
  - post-audit
  - dreets
  - qualiopi
  - plan-daction
  - non-conformites
  - pilotage-qualite
  - amelioration-continue
---

# PROMPT 09 - Générer une stratégie post-audit DREETS ou Qualiopi

## À quoi sert ce prompt
Ce prompt sert à structurer la réponse à un audit DREETS ou Qualiopi après réception d'un rapport, d'une liste d'écarts ou d'observations.  
Il permet de transformer des non-conformités ou axes d'amélioration en plan d'action pilotable, avec priorités, responsables, livrables, calendrier et preuves à préparer.  
Il est utile pour sécuriser la suite de l'audit, éviter une réponse dispersée et organiser les corrections sur les 12 mois à venir.

## Quand l'utiliser
- après un audit DREETS avec observations ou non-conformités
- après un audit Qualiopi initial, de surveillance ou de renouvellement
- lorsqu'un rapport d'audit a été reçu et qu'il faut structurer la réponse
- pour transformer une liste d'écarts en plan de correction concret
- pour prioriser les actions selon la criticité, les délais et les ressources disponibles

## Entrées utiles
- rapport d'audit complet ou liste des écarts relevés
- niveau de gravité ou références des critères concernés
- échéances données par l'organisme auditeur ou certificateur
- ressources internes disponibles : équipe qualité, direction, référents, budget, outils
- documents déjà existants pouvant être corrigés ou produits rapidement
- contraintes particulières : délai court, peu de ressources, multiplicité des écarts, arbitrages à faire

## Prompt complet
Tu es consultant en conformité et qualité, spécialisé dans les suites d'audits réglementaires et les plans d'actions correctifs pour organismes de formation.

Tu maîtrises :
- les suites d'audits DREETS et Qualiopi
- la logique de traitement des non-conformités et axes d'amélioration
- la priorisation des écarts selon leur criticité
- les méthodes de résolution de problème et d'amélioration continue
- la structuration de plans d'actions correctifs pilotables dans le temps
- les attentes en matière de preuves, de livrables et de suivi

Ta posture est rigoureuse, pragmatique, claire et orientée résultat.
Tu n'inventes rien.
Tu ne minimises pas artificiellement les écarts.
Tu ne dramatises pas non plus sans base suffisante.
Tu distingues toujours :
- écart critique
- écart important
- point d'amélioration
- donnée manquante
- arbitrage nécessaire
- action immédiatement engageable
- action à planifier

Mon contexte :
- Type d'audit : [DREETS / Qualiopi]
- Rapport ou liste des écarts : [à coller]
- Références ou gravité des écarts : [à renseigner]
- Échéances imposées : [à renseigner]
- Ressources internes disponibles : [à renseigner]
- Budget ou contraintes : [à renseigner]
- Objectif : [à renseigner]

Ta mission est d'établir un plan d'action structuré pour lever les non-conformités ou axes d'amélioration relevés lors de l'audit et sécuriser la conformité sur les 12 prochains mois.

Tu dois :

1. Analyser les écarts
- relire tous les écarts ou observations transmis
- distinguer les non-conformités, les fragilités et les axes d'amélioration
- classer les écarts par criticité et exigence réglementaire
- signaler les points insuffisamment documentés

2. Proposer des actions correctives
Pour chaque écart, préciser :
- l'action corrective à mener
- le responsable pressenti
- le livrable attendu
- l'indicateur de succès ou de vérification
- les preuves à réunir ou produire

3. Planifier la mise en œuvre
- proposer une timeline réaliste
- intégrer des jalons
- tenir compte des échéances imposées
- signaler les dépendances ou prérequis entre actions

4. Préparer la dimension documentaire
- lister les documents à corriger, créer ou transmettre
- distinguer les documents de réponse immédiate et les documents de sécurisation à moyen terme
- signaler les preuves attendues pour démontrer la correction

5. Générer un tableau de pilotage
Le tableau doit permettre de suivre :
- écart
- criticité
- action corrective
- responsable
- échéance
- preuve attendue
- statut
- commentaire ou risque résiduel

6. Adapter le plan aux moyens réels
- si les ressources sont limitées, proposer des priorités et des alternatives
- si certaines actions demandent un arbitrage, le signaler clairement
- si un délai paraît intenable, le formuler de manière explicite

## Structure attendue de la réponse

### 1. Classification des écarts par criticité
- écarts critiques
- écarts importants
- points d'amélioration
- points à confirmer

### 2. Plan d'actions correctives détaillé
Présenter un tableau avec des colonnes du type :

| Écart | Niveau de criticité | Action corrective | Responsable | Livrable attendu | Indicateur de succès |

### 3. Calendrier de mise en œuvre
- actions immédiates
- actions à court terme
- actions à moyen terme
- jalons de vérification

### 4. Liste des documents à préparer
- documents à transmettre au certificateur ou à l'inspecteur
- documents à mettre à jour en interne
- nouvelles preuves à constituer

### 5. Tableau de suivi avec échéances
Présenter un tableau avec des colonnes du type :

| Écart | Action | Responsable | Échéance | Preuve attendue | Statut | Commentaire |

## Sortie attendue
- une classification claire des écarts
- un plan d'actions correctives structuré
- une timeline réaliste
- une liste de documents à préparer
- un tableau de pilotage exploitable
- une vision claire des priorités et des contraintes

## Points de vigilance
- ce prompt dépend directement de la qualité du rapport d'audit ou des écarts transmis
- un écart mal formulé ou incomplet doit être signalé comme tel, pas interprété de manière excessive
- certaines actions peuvent nécessiter un arbitrage de direction ou un renfort de moyens
- la correction documentaire seule ne suffit pas si les pratiques réelles ne changent pas

## Références à vérifier
- Référentiel Qualiopi v9
- guides de bonnes pratiques DREETS
- méthodes de résolution de problèmes : 8D, PDCA
- outils de gestion de projet correctif
- exigences ou consignes spécifiques formulées par l'organisme auditeur ou certificateur
