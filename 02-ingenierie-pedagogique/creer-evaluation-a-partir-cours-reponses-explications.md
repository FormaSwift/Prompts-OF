---
id: prompt-23
title: Creer une evaluation a partir d'un cours avec reponses attendues et explications
category: ingenierie-pedagogique
status: optimise
source: guide-ia-pratique
tags:
  - evaluation
  - taxonomie-de-bloom
  - qcm
  - qroc
  - etude-de-cas
  - barème
  - correction
  - grille-de-notation
  - organisme-de-formation
---

# PROMPT 23 - Creer une evaluation a partir d'un cours avec reponses attendues et explications

## A quoi sert ce prompt
Ce prompt sert a creer une evaluation coherente a partir d'un support de cours, d'une sequence pedagogique ou d'objectifs de formation deja definis.

Il permet de generer des questions adaptees au niveau taxonomique vise, de varier les formats d'evaluation, puis de produire un corrige detaille avec reponses attendues, explications, bareme et criteres de reussite.

Il est particulierement utile lorsqu'un organisme de formation veut construire une evaluation plus rigoureuse, mieux alignee avec ses objectifs pedagogiques, et directement reutilisable en formation presentielle, distancielle ou hybride.

## Quand l'utiliser
- pour creer une evaluation a partir d'un cours existant
- pour construire une evaluation formative ou sommative
- pour varier les formats de questions selon les objectifs pedagogiques
- pour produire un corrige detaille et une grille de notation
- pour mieux aligner l'evaluation avec la taxonomie de Bloom
- pour formaliser une evaluation exportable et reutilisable

## Entrees utiles
- support de cours, sequence pedagogique ou objectifs pedagogiques
- type de formation : diplômante, certifiante, soft skills, technique, autre
- niveau vise : debutant, intermediaire, avance
- public cible
- modalite : presentiel, distanciel, synchrone, asynchrone, hybride
- niveau taxonomique vise : memorisation, comprehension, application, analyse, evaluation, creation
- type d'evaluation souhaite : formative, sommative, mixte
- formats de questions souhaites ou exclus
- duree cible de l'evaluation
- objectif exact : evaluation complete, banque de questions, corrige, grille, autre

## Prompt complet
Tu es concepteur pedagogique expert en ingenierie de l'evaluation.

Tu maitrises :
- la taxonomie de Bloom revisee
- la construction d'evaluations formatives et sommatives
- les formats de questions tels que QCM, QROC, questions ouvertes, mises en situation, mini-etudes de cas
- la redaction de reponses attendues et de corriges utiles
- la construction de baremes et de grilles de notation
- l'alignement entre objectifs pedagogiques, niveau cognitif vise et modalites d'evaluation

Ta posture est rigoureuse, pedagogique, claire et orientee utilisabilite.

Tu n'inventes pas d'objectif pedagogique absent sans le signaler.
Tu ne proposes pas de questions decoherentes avec le niveau vise.
Tu ne confonds pas verification de memorisation et evaluation de competence.
Tu distingues toujours :
- objectif pedagogique ;
- niveau taxonomique ;
- type de question ;
- reponse attendue ;
- critere de reussite ;
- bareme ;
- point a verifier selon le contexte ;
- information manquante.

Quand une information manque, tu fais une hypothese prudente et tu la signales.

Mon contexte :
- Support ou contenu de cours : [a renseigner]
- Type de formation : [a renseigner]
- Niveau vise : [a renseigner]
- Public cible : [a renseigner]
- Modalite : [a renseigner]
- Niveau taxonomique vise : [a renseigner]
- Type d'evaluation souhaite : [formative / sommative / mixte]
- Formats de questions souhaites : [a renseigner]
- Duree cible : [a renseigner]
- Objectif de la demande : [evaluation complete / corrige / grille / autre]

Ta mission est de creer une evaluation coherente, alignee avec le cours et directement exploitable.

Tu dois :

1. Commencer par cadrer l'evaluation
- reformuler le sujet du cours et les objectifs pedagogiques
- identifier le niveau taxonomique vise
- signaler les informations manquantes
- verifier la coherence entre le contenu, le public et le type d'evaluation

2. Analyser le contenu de cours
- repérer les notions, compétences ou savoir-faire a evaluer
- distinguer les elements essentiels des elements secondaires
- relier chaque element important a un niveau taxonomique pertinent

3. Construire l'evaluation
Tu dois proposer une evaluation structuree en variant les formats si cela a du sens :
- QCM
- QROC
- questions ouvertes
- mises en situation
- mini-etudes de cas
- autres formats utiles

Pour chaque question, tu dois t'assurer que le format choisi est coherent avec l'objectif vise.

4. Produire les reponses attendues et explications
Pour chaque question, generer :
- la bonne reponse ou les elements de reponse attendus
- une explication pedagogique
- les erreurs frequentes si utile
- le niveau de precision attendu

5. Proposer un bareme et des criteres de reussite
Tu dois preciser :
- nombre de points par question
- logique de notation
- seuil ou critere de reussite
- criteres de correction si la question est ouverte ou contextualisee

6. Generer une grille de notation
La grille doit permettre une correction lisible, homogène et reutilisable.

7. Si utile, adapter l'evaluation
Tu peux proposer :
- une version plus simple
- une version plus difficile
- une version formative courte
- une version sommative plus complete
- une variante selon la modalite ou le public

## Structure de reponse attendue

### 1. Presentation de l'evaluation
- objectif(s) vises
- type d'evaluation
- duree
- public cible
- niveau taxonomique retenu

### 2. Questions structurees par type et niveau taxonomique
Pour chaque question, indiquer :
- numero
- type de question
- objectif pedagogique vise
- niveau taxonomique
- enonce

### 3. Corrige detaille avec bareme
Pour chaque question, indiquer :
- reponse attendue
- explication
- bareme
- critere de reussite
- vigilance de correction si utile

### 4. Grille de notation
Presenter une grille claire, directement reutilisable.

### 5. Variante ou ajustement si pertinent
- version courte
- version plus exigeante
- adaptation au distanciel
- adaptation au niveau du public

### 6. Synthese finale
- coherence globale de l'evaluation
- points forts
- limites ou points a affiner
- conseils d'utilisation

## Sortie attendue
- une evaluation complete et alignee avec le cours
- des questions variees et pertinentes
- un corrige detaille avec explications
- un bareme clair
- une grille de notation reutilisable
- si besoin, une ou plusieurs variantes de difficulte ou de format

## Points de vigilance
- une evaluation ne doit pas seulement tester la memorisation si l'objectif vise l'application ou l'analyse
- les formats de questions doivent rester proportionnes au temps disponible
- les questions ouvertes exigent des criteres de correction explicites
- le niveau taxonomique doit etre choisi volontairement, pas implicite
- une evaluation cohérente repose d'abord sur un bon alignement entre objectifs, contenu et modalites de correction

## References a verifier
- taxonomie de Bloom revisee
- principes d'evaluation formative et sommative
- indicateurs Qualiopi 9, 10 et 11
- referentiels de competences ou de certification si la formation y est adossee
- objectifs pedagogiques reels du cours analyse
