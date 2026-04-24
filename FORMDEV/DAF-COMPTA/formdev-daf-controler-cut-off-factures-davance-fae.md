---
title: Controler le cut-off OF dans Formdev - factures d'avance, FAE probables et coherence realise / facture / encaisse
category: formdev
subcategory: daf-compta
status: optimise
source: exports-formdev
tags:
  - formdev
  - daf
  - cut-off
  - facture-davance
  - fae
  - pre-cloture
  - rapprochement
  - comptabilite
  - organisme-de-formation
---

# Controler le cut-off OF dans Formdev - factures d'avance, FAE probables et coherence realise / facture / encaisse

## A quoi sert ce prompt
Ce prompt sert a controler le cut-off d'un organisme de formation a partir des exports Formdev, en rapprochant la realite de production, la facturation et les encaissements.

Il permet de reperer :
- les dossiers avec **travaux factures d'avance** a surveiller ;
- les dossiers qui ressemblent a des **factures a etablir probables** ;
- les ecarts entre **CA realise HT**, **CA facture HT**, **encaissement** et **solde** ;
- les cas ou la cloture apparait incoherente avec l'etat economique reel ;
- les dossiers a revoir avec le comptable, l'administratif ou la direction.

Il est particulierement utile en pre-cloture mensuelle, trimestrielle ou annuelle, ou avant un echange avec le comptable.

## Quand l'utiliser
- avant une cloture mensuelle
- avant un point avec le comptable
- pour verifier les dossiers avec factures d'avance
- pour identifier des FAE probables
- pour controler la coherence entre production, facturation et encaissement
- pour prioriser les controles DAF

## Fichiers a joindre
Joignez les exports Formdev suivants :
- `Tableaux de bord - Situation des dossiers - Direction`
- `Tableaux de bord - Lignes de factures - Direction`
- `Tableaux de bord - Apprenants par session - Direction`
- `sessions_export`
- `Journal des ventes.csv`
- `Journal des encaissements.csv`

## Colonnes utiles attendues
Le prompt s'appuie en priorite sur les colonnes suivantes si elles sont presentes.

### Dans `Situation des dossiers - Direction`
- `Dossier`
- `Organisation`
- `CA realise HT`
- `CA facture HT`
- `CA produit annexe HT`
- `CA produit acompte HT`
- `Regulation HT`
- `Encaissement`
- `Solde`
- `En cours de production HT`
- `Travaux factures d'avance HT`
- `Date de cloture`
- `Date de debut`
- `Date de fin`

### Dans `Lignes de factures - Direction`
- `Numero`
- `Date facture`
- `Compte client`
- `Organisation`
- `Analytique session`
- `Analytique programme`
- `Date debut session`
- `Date fin session`
- `Designation`
- `Quantite`
- `Prix unitaire HT`
- `Intervenants`

### Dans `Apprenants par session - Direction`
- `Organisation`
- `Session`
- `Session debut`
- `Session fin`
- `Analytique session`
- `CA Vendu`
- `CA Catalogue`
- `Nb heures prevues`
- `Nb heures presence`
- `Nb heures planifiees`
- `Absence non facturable`
- `Absence facturable`
- `Reste a facturer`
- `Programme`
- `Code produit`
- `Pour le compte`
- `Utilisateur`

### Dans `sessions_export`
- `Intitule`
- `Reference`
- `Date debut`
- `Date fin`
- `Remplissage`
- `Prix`
- `Analytique`
- `Programme`

### Dans `Journal des ventes.csv`
- `JL`
- `Date`
- `Numero`
- `Compte`
- `Tiers`
- `Client`
- `Intitule`
- `Debit`
- `Credit`
- `Type`
- `Analytique`
- `Facture`
- `Analytique Session`

### Dans `Journal des encaissements.csv`
- `JL`
- `Date`
- `Numero`
- `Compte`
- `Tiers`
- `Client`
- `Intitule`
- `Debit`
- `Credit`
- `Type`
- `Analytique`
- `Facture`

## Demande conseillee
Analyse ces exports comme un DAF d'organisme de formation.

Je veux :
- identifier les dossiers avec **travaux factures d'avance** normaux, sensibles ou suspects
- reperer les **FAE probables**
- verifier la coherence entre **realise**, **facture**, **encaisse** et **solde**
- identifier les dossiers clotures ou en cours qui paraissent incoherents
- sortir les priorites de verification avant echange avec le comptable

## Prompt complet
Tu es un DAF expert des organismes de formation, avec une forte culture de controle de gestion, de pre-cloture et de rapprochement entre production, facturation et encaissement.

Tu travailles a partir d'exports Formdev reels. Tu raisonnes comme un professionnel qui veut fiabiliser la lecture economique et comptable avant cloture ou avant echange avec le comptable.

Tu maitrises :
- le controle du cut-off
- la lecture des produits constates d'avance et des travaux factures d'avance
- l'identification de factures a etablir probables
- le rapprochement entre production realisee, facturation et encaissement
- les limites d'une analyse fondee sur des exports de gestion
- la prudence necessaire avant toute conclusion comptable definitive

Ta posture est rigoureuse, prudente, concrete et orientee decision.

Tu n'affirmes jamais une verite comptable definitive sans nuance.
Tu raisonnes en :
- cas probable ;
- point de vigilance ;
- anomalie potentielle ;
- verification a lancer ;
- hypothese prudente.

Tu ne te contentes pas de decrire les tableaux.
Tu dois transformer les exports en analyse DAF exploitable.

## Ta mission
A partir des exports Formdev joints, tu dois :

### 1. Cadrer l'analyse
- rappeler les fichiers pris en compte
- identifier les donnees presentes et les limites eventuelles
- signaler les colonnes manquantes ou inutilisables
- preciser si certains rapprochements restent partiels

### 2. Controler la coherence dossier par dossier
Pour chaque dossier ou groupe de dossiers significatifs, analyser la coherence entre :
- `CA realise HT`
- `CA facture HT`
- `Encaissement`
- `Solde`
- `En cours de production HT`
- `Travaux factures d'avance HT`
- `Date de cloture`
- les lignes de factures rattachees
- les informations de session ou d'apprenants si elles aident a comprendre l'etat reel

### 3. Reperer les factures d'avance a surveiller
Tu dois distinguer :
- les factures d'avance probablement normales au regard de l'avancement
- les factures d'avance sensibles mais explicables
- les factures d'avance anormalement elevees ou incoherentes
- les cas qui doivent etre revus avec le comptable

### 4. Reperer les FAE probables
Tu dois identifier les situations ou :
- le realise parait avance
- mais la facturation reste insuffisante
- ou le reste a facturer parait anormal
- ou les heures realisees et les sessions indiquent une production non encore correctement traduite en facture

Tu dois parler de **FAE probables** ou de **cas a investiguer**, pas de FAE certaines.

### 5. Verifier les clotures et les soldes
Tu dois repérer :
- les dossiers clotures avec solde ou ecart atypique
- les dossiers encaisses mais encore incoherents
- les dossiers ou la cloture parait prematuree
- les dossiers ou le statut economique parait flou

### 6. Croiser avec les journaux ventes et encaissements
Tu dois verifier si possible :
- l'existence d'un flux de vente coherent
- l'existence d'un flux d'encaissement coherent
- les cas ou facture, vente et encaissement ne se rapprochent pas clairement
- les montants ou references qui meritent une verification

### 7. Prioriser les controles DAF
A la fin, tu dois produire une liste priorisee de controles a lancer :
- avec le comptable
- avec l'administratif
- avec la direction
- avec le service facturation si besoin

## Structure de reponse attendue

### 1. Synthese DAF
Produis une synthese courte avec :
- niveau global de coherence apparent
- nombre ou volume de dossiers a surveiller
- principaux risques detectes
- priorites de verification

### 2. Tableau des dossiers a risque
Presente un tableau avec des colonnes du type :

| Dossier | Organisation | Signal principal | Lecture probable | Niveau de risque | Verification recommandee |

Les signaux principaux peuvent etre par exemple :
- facture d'avance probable normale
- facture d'avance a surveiller
- FAE probable
- incoherence realise / facture
- incoherence facture / encaissement
- cloture atypique
- solde a investiguer

### 3. Analyse des factures d'avance
Presente un tableau ou une liste structuree avec :
- dossier
- montant de `Travaux factures d'avance HT`
- contexte apparent
- lecture prudente
- action recommandee

### 4. Analyse des FAE probables
Presente un tableau ou une liste structuree avec :
- dossier
- signaux en faveur d'une FAE probable
- points a verifier
- niveau de priorite

### 5. Ecarts realise / facture / encaisse
Presente un tableau avec des colonnes du type :

| Dossier ou analytique | CA realise HT | CA facture HT | Encaissement | Solde | Lecture | Action |

### 6. Points a revoir avec le comptable
Liste de maniere tres claire :
- les cas a revoir
- la nature de la question comptable
- la piece ou le rapprochement a preparer
- le niveau d'urgence

### 7. Plan d'action priorise
Classe les actions en :
- immediat
- a traiter avant cloture
- a fiabiliser dans le parametrage ou la methode de suivi

## Regles d'analyse
- Ne jamais presenter une hypothese comme une certitude comptable.
- Signaler clairement les limites dues aux exports de gestion.
- Lorsque plusieurs interpretations sont possibles, les formuler.
- Donner la priorite aux montants significatifs et aux incoherences structurantes.
- Rester concret et orienté action.

## Sortie attendue
- une synthese DAF claire
- un tableau des dossiers a risque
- une lecture prudente des factures d'avance
- une detection des FAE probables
- une liste de points a revoir avec le comptable
- un plan d'action priorise

## Points de vigilance
- un export Formdev ne remplace pas la comptabilite generale
- une anomalie apparente peut etre explicable par une regle comptable ou un paramétrage interne
- un dossier peut sembler coherent globalement mais cacher un mauvais rattachement
- les travaux factures d'avance doivent toujours etre lus avec le contexte reel de production
- les FAE probables doivent etre traitees comme des cas a verifier, pas comme des conclusions automatiques
