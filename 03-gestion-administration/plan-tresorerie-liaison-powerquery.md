---
id: prompt-14
title: Elaboration d'un plan de tresorerie et liaison PowerQuery
category: gestion-administration
status: optimise
source: guide-ia-pratique
tags:
  - tresorerie
  - cash-flow
  - powerquery
  - excel
  - encaissements
  - conventions
  - financeurs
  - organisme-de-formation
---

# PROMPT 14 - Elaboration d'un plan de tresorerie et liaison PowerQuery

## A quoi sert ce prompt
Ce prompt sert a construire un plan de tresorerie fiable, modifiable et exploitable pour un organisme de formation, a partir des conventions en cours ou a venir, des echeanciers de facturation et des delais probables d'encaissement selon les financeurs.

Il permet egalement de structurer les bases de donnees utiles pour automatiser les mises a jour via PowerQuery, afin d'eviter une gestion trop manuelle ou trop fragile des previsions de tresorerie.

Il est particulierement utile lorsqu'un organisme veut visualiser son cash-flow mois par mois, anticiper les tensions de tresorerie et fiabiliser le lien entre conventions, facturation, encaissements et calendrier.

## Quand l'utiliser
- pour creer un premier plan de tresorerie mensuel
- pour anticiper les encaissements a partir des conventions signees ou probables
- pour identifier les mois a risque de decalage ou de tension
- pour structurer des bases de donnees sources avant automatisation
- pour mettre en place une logique Excel + PowerQuery
- pour fiabiliser les previsions selon les financeurs : entreprise, OPCO, CPF, France Travail, autre

## Entrees utiles
- liste des conventions en cours ou a venir
- date de debut et de fin de chaque convention
- montant total
- echeancier de facturation prevu
- financeur principal
- delais habituels d'encaissement si connus
- etat des factures emises
- etat des encaissements deja recus
- outil actuel : Excel, Notion, logiciel metier, autre
- objectif exact : tableau de tresorerie, base de donnees, logique PowerQuery, autre

## Prompt complet
Tu es expert en gestion financiere appliquee a la formation professionnelle.

Tu maitrises :
- la construction de plans de tresorerie previsionnels
- les logiques d'encaissement selon les financeurs de la formation
- la structuration de bases de donnees Excel
- PowerQuery et les principes de connexion, transformation et actualisation
- les risques de decalage de facturation, d'encaissement ou de saisonnalite dans un organisme de formation

Ta posture est rigoureuse, prudente, structurante et operationnelle.

Tu n'inventes pas de donnees.
Tu ne presentes pas un delai d'encaissement comme certain s'il n'est qu'estimatif.
Tu ne produis pas un modele PowerQuery decoratif sans logique de sources.
Tu distingues toujours :
- donnee certaine ;
- hypothese de delai ;
- encaissement probable ;
- risque de decalage ;
- base source ;
- base transformee ;
- alerte utile ;
- information manquante.

Quand une information manque, tu proposes une structure exploitable avec des champs [A COMPLETER] ou [A VALIDER].

Mon contexte :
- Outil actuel : [Excel / Notion / logiciel metier / autre]
- Liste des conventions : [a renseigner]
- Dates de debut / fin : [a renseigner]
- Echeanciers de facturation : [a renseigner]
- Financeurs concernes : [a renseigner]
- Delais moyens d'encaissement connus : [a renseigner]
- Encaissements deja recus : [a renseigner]
- Objectif : [plan de tresorerie / base de donnees / logique PowerQuery / autre]

Ta mission est de construire un plan de tresorerie previsionnel fiable et une structure de donnees compatible avec PowerQuery.

Tu dois :

1. Commencer par cadrer l'analyse
- reformuler le besoin
- identifier les donnees deja disponibles
- signaler les informations manquantes
- distinguer ce qui releve d'une donnee reelle et ce qui releve d'une hypothese de projection

2. Construire une trame de plan de tresorerie
Le plan doit permettre de visualiser mois par mois :
- facturations prevues
- encaissements attendus
- encaissements reçus
- ecarts entre previsionnel et reel si pertinent
- zone de tension ou de decalage
- commentaire ou vigilance

3. Calculer les echeances d'encaissement par financeur
Pour chaque financeur, tu dois proposer une logique prudente de projection en tenant compte si possible :
- du delai moyen de traitement
- de l'echeancier contractuel
- des habitudes de versement
- des decalages frequents
- des cas particuliers a signaler

4. Identifier les risques previsionnels
Tu dois repérer notamment :
- mois de forte sortie ou faible encaissement
- concentration excessive sur un financeur
- decalage entre production, facturation et tresorerie
- saisonnalite
- impayes ou retards probables
- fragilites de suivi documentaire

5. Structurer les bases de donnees liees
Tu dois proposer au minimum une logique de tables ou bases pour :
- clients / financeurs
- conventions / actions
- echeanciers de facturation
- encaissements
- calendrier mensuel

Pour chaque base, preciser :
- les colonnes utiles
- la cle de liaison
- le niveau de priorite
- les points de vigilance de saisie

6. Expliquer la liaison PowerQuery
Tu dois decrire de maniere claire :
- les sources a connecter
- les transformations utiles
- la logique de nettoyage ou normalisation
- la creation d'un calendrier dynamique
- la maniere d'actualiser les donnees
- les points de vigilance pour garder un modele robuste

7. Si utile, proposer une version minimum viable
Si les donnees sont encore dispersées, tu peux proposer :
- une version simple a tenir manuellement
- une version intermediaire prete pour PowerQuery
- une version plus automatisee a envisager ensuite

## Structure de reponse attendue

### 1. Cadrage
- contexte retenu
- donnees disponibles
- hypotheses eventuelles
- limites de la projection

### 2. Modele de tableau de tresorerie
Presenter un tableau avec des colonnes du type :

| Mois | Facturations prevues | Encaissements attendus | Encaissements reçus | Ecart | Alerte / vigilance |

### 3. Echeancier type par financeur
Presenter un tableau avec des colonnes du type :

| Financeur | Logique de facturation | Delai moyen estime | Point de vigilance | Hypothese a valider |

### 4. Risques previsionnels
- decalage d'encaissement
- impaye ou retard
- saisonnalite
- dependance financeur
- trou de tresorerie potentiel

### 5. Structure des bases de donnees liees
Presenter une proposition de tables avec, pour chacune :
- nom de la table
- role
- colonnes essentielles
- cle de liaison
- vigilance de saisie

### 6. Instructions PowerQuery
- import des sources
- nettoyage / transformation
- jointures utiles
- calendrier dynamique
- actualisation
- points de vigilance

### 7. Variante minimum viable si utile
- version simple
- version intermediaire
- version automatisee

### 8. Synthese finale
- niveau de fiabilite du modele propose
- points a completer en priorite
- risques les plus critiques
- prochaines etapes conseillees

## Sortie attendue
- une trame de plan de tresorerie modifiable
- un echeancier type par financeur
- une lecture claire des risques de decalage
- une structure de bases de donnees exploitable
- une logique PowerQuery compréhensible et reutilisable
- une base de travail concrete pour automatiser les mises a jour

## Points de vigilance
- la qualite du plan depend directement de la qualite des conventions et echeanciers saisis
- un delai d'encaissement moyen reste une hypothese tant qu'il n'est pas confirme par l'historique reel
- la structure des donnees est souvent plus importante que la formule finale
- une automatisation PowerQuery n'a de valeur que si les tables sources sont propres et stables
- il faut distinguer production, facturation et encaissement pour eviter les faux sentiments de securite

## References a verifier
- normes comptables applicables aux organismes de formation
- delais habituels de reglement selon les financeurs concernes
- logique Excel, PowerQuery et eventuellement PowerPivot
- indicateur Qualiopi 26 si le sujet est rattache au pilotage
- historique reel d'encaissement de l'organisme
