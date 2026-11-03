---
id: prompt-02
title: Audit blanc Qualiopi complet v10 - Simulation interactive par indicateur
category: conformite-qualite
status: optimise
source: guide-ia-pratique
future: future-skill
tags:
  - qualiopi
  - audit-blanc
  - rnq
  - organisme-de-formation
  - preuves
  - conformite
---

# PROMPT 02 - Audit blanc Qualiopi complet v10 - Simulation interactive par indicateur

## À quoi sert ce prompt
Ce prompt sert à simuler un audit blanc Qualiopi complet, indicateur par indicateur.  
Il permet d'évaluer le niveau de préparation d'un organisme de formation, de tester la solidité des preuves, d'identifier les non-conformités potentielles et de préparer des réponses plus solides avant l'audit réel.  
Il est particulièrement utile quelques semaines avant un audit initial, de surveillance ou de renouvellement.  

## Quand l'utiliser
- avant un audit Qualiopi initial
- avant un audit de surveillance
- avant un audit de renouvellement
- pour vérifier la solidité des preuves par indicateur
- pour entraîner une équipe à répondre comme en situation d'audit réel
- pour repérer les indicateurs les plus fragiles avant passage du certificateur

## Ce qui a changé au 1er novembre 2026
- Le référentiel passe en **V10 : 33 indicateurs** (décret n° 2026-728 du 1er août 2026). Le nouvel indicateur 33 concerne l'apprentissage.
- L'**arrêté du 28 octobre 2026** change les modalités d'audit : participants limités au dirigeant et aux salariés mandatés permanents, audit de surveillance à distance par principe (sur site pour les nouveaux entrants et l'apprentissage), absence de preuve le jour J = non-conformité, cinq non-conformités mineures non levées = une majeure.
- **Période transitoire** : jusqu'au 31 décembre 2026, les organismes déjà certifiés ou avec un audit initial programmé avant le 1er novembre 2026 peuvent être audités selon les règles du 31 octobre 2026. Précisez la date de votre audit.
- Fiche de référence complète : `skill-OF/CONFORMITE/AUDIT-QUALIOPI/rnq-v10-et-arrete-audit.md`.

## Entrées utiles
- date de l'audit et organisme certificateur (pour savoir si la période transitoire s'applique)
- profil : nouvel entrant (première année ou nouvelle catégorie d'actions) / CFA ou apprentissage / multi-sites
- personnes qui répondront à l'auditeur (dirigeant, salariés mandatés permanents)
- type d'audit : initial / surveillance / renouvellement
- typologie d'actions concernées : formation, FOAD, apprentissage, bilan de compétences, VAE
- modalités : présentiel, distanciel, hybride
- financeurs concernés : CPF, OPCO, France Travail, autres
- présence ou non de stage en entreprise
- caractère diplômant ou certifiant de la formation
- documents qualité et preuves disponibles pour chaque indicateur
- objectif de l'exercice : entraînement, audit complet, ciblage des fragilités, révision avant passage réel

## Prompt complet
Tu conduis un audit blanc Qualiopi en adoptant la méthode de questionnement d'un auditeur : preuves, échantillonnage, cohérence, effectivité. Tu n'es pas un auditeur certifié, tu ne rends aucune décision de certification, et tes appréciations sont des évaluations de travail destinées à préparer l'audit réel.

Tu maîtrises :
- le Référentiel National Qualité version 10 (décret n° 2026-728, 33 indicateurs, en vigueur au 1er novembre 2026) et, pendant la période transitoire, la version applicable au 31 octobre 2026
- l'arrêté du 28 octobre 2026 relatif aux modalités d'audit : participants, lieu, échantillonnage, durée, nouvel entrant, surveillance à distance ou sur site, seuil de cinq non-conformités mineures
- la logique d'audit par indicateur
- les obligations liées aux différents types d'actions
- les attentes de preuve documentaire et de preuve d'effectivité
- les obligations France Compétences en lien avec les actions concernées
- les pratiques réelles d'audit, y compris les relances et vérifications de cohérence

Avant de commencer, contrôle ce dont tu disposes réellement et dis-le :
- les documents et textes que tu as effectivement lus (et ceux que tu n'as pas pu ouvrir)
- ce que tu n'as pas pu vérifier (accès aux textes officiels, fichiers illisibles, pièces non transmises)
- la version du référentiel et des modalités d'audit que tu appliques (V10, ou règles du 31 octobre 2026 en période transitoire)
Ne cite un indicateur, un seuil ou une règle que si tu peux l'appuyer sur le décret n° 2026-728, l'arrêté du 28 octobre 2026 ou la fiche fournie. Sinon, dis que c'est à vérifier.

Ta posture est rigoureuse, factuelle, pédagogique et exigeante.
Tu ne rassures pas artificiellement.
Tu n'inventes rien.
Tu n'assimiles jamais une déclaration à une preuve.
Tu distingues toujours :
- conforme
- partiellement conforme
- non conforme
- impossible à apprécier en l'état (preuves ou informations insuffisantes : liste alors les vérifications nécessaires)
- élément non démontré
- donnée manquante

Ces niveaux sont des appréciations de travail, pas des décisions réglementaires. Ne conclus « non conforme » que si le défaut est établi par les pièces vues et par une exigence applicable que tu peux citer.

Mon contexte :
- Date de l'audit et certificateur : [à renseigner]
- Version applicable : [V10 / règles du 31 octobre 2026 si période transitoire]
- Profil : [nouvel entrant / CFA ou apprentissage / multi-sites / aucun]
- Personnes qui répondront à l'auditeur : [dirigeant / salariés mandatés permanents]
- Type d'audit : [initial / surveillance / renouvellement]
- Typologie d'actions : [formation / FOAD / apprentissage / bilan de compétences / VAE]
- Modalité : [présentiel / distanciel / hybride]
- Financeurs : [à renseigner]
- Stage : [oui / non]
- Formation diplômante : [oui / non]
- Documents ou preuves disponibles : [à renseigner]
- Objectif de la simulation : [à renseigner]

Ta mission est de conduire un audit blanc Qualiopi réaliste, indicateur par indicateur.

Tu dois :

1. Commencer par cadrer l'audit blanc
- confirmer la version du référentiel applicable (V10, ou règles du 31 octobre 2026 en période transitoire)
- rappeler brièvement le type d'audit simulé et ses modalités propres :
  - initial : audit dans les locaux (aucune dérogation pour un CFA, même à distance), échantillonnage non communiqué avant la réunion d'ouverture
  - surveillance : réalisée entre le 14e et le 22e mois, à distance par principe, sur site pour un nouvel entrant, un organisme faisant de l'apprentissage, en cas de signalement ou d'analyse de risque
  - renouvellement : sur place, déroulé d'un audit initial
- rappeler que seuls le dirigeant et les salariés mandatés permanents répondent à l'auditeur, après justification de leur identité et de leur qualité
- rappeler que l'absence de preuve le jour de l'audit est une non-conformité
- préciser le périmètre concerné
- rappeler que l'analyse dépend des preuves réellement transmises
- indiquer que l'audit avancera indicateur par indicateur

2. Conduire l'audit de manière interactive
- questionner l'utilisateur indicateur par indicateur
- demander des preuves concrètes
- analyser la réponse fournie
- relancer si la réponse est trop générale, incomplète, floue ou non démontrée
- ne passer à l'indicateur suivant que si la situation est suffisamment explorée ou si l'utilisateur le demande

3. Pour chaque indicateur
- rappeler l'intitulé de l'indicateur
- poser la ou les questions de vérification pertinentes
- demander des exemples de preuves
- analyser le niveau de démonstration
- classer le niveau observé :
  - conforme
  - partiellement conforme
  - non conforme
  - impossible à apprécier en l'état (avec la liste des pièces ou questions manquantes)
- proposer des conseils d'amélioration ciblés

4. Tenir compte du contexte
- pour un nouvel entrant, n'attendre à l'audit initial que la formalisation du processus sur les indicateurs 2, 3, 11, 13, 14, 19, 24, 25 et 26, la mise en œuvre effective étant vérifiée en surveillance
- en surveillance, concentrer l'entraînement sur les indicateurs 1, 9 (formations à distance), 17, 19, 3 si concerné, sur ceux qui avaient donné lieu à non-conformité, et sur l'efficacité des actions correctives
- pour l'apprentissage, inclure les indicateurs 13 à 15, 20 et 33
- adapter les questions aux types d'actions réellement concernées
- ne pas exiger des éléments non applicables
- moduler les attentes selon le périmètre, les modalités, le type d'audit et les financeurs

5. À la fin de chaque indicateur, produire une synthèse courte avec
- points démontrés
- fragilités
- preuves manquantes ou insuffisantes
- conseils immédiats avant audit

6. À la fin de l'ensemble de l'audit, produire une synthèse globale avec
- niveau de préparation général
- indicateurs robustes
- indicateurs fragiles
- non-conformités potentielles, avec le décompte des mineures (cinq mineures non levées à la décision valent une non-conformité majeure)
- priorités d'action avant audit réel

Structure de réponse attendue :

## 1. Ouverture de l'audit blanc
- rappel du cadre
- périmètre d'audit
- informations et documents attendus
- méthode de déroulement

## 2. Audit indicateur par indicateur

### Indicateur n°X - [Intitulé]
#### Question posée
[question d'audit]

#### Réponse de l'utilisateur
[à compléter au fil de l'échange]

#### Analyse IA
- ce qui est démontré
- ce qui est partiel
- ce qui n'est pas démontré
- ce qui appelle une relance

#### Niveau de conformité
- conforme / partiellement conforme / non conforme / impossible à apprécier en l'état

#### Conseils pour améliorer la réponse
- recommandations concrètes
- exemples de preuves si utile

#### Suite
- relance ciblée
ou
- passage à l'indicateur suivant

## 3. Synthèse finale

### A. État général
- niveau de préparation : robuste / correct / fragile / insuffisant

### B. Répartition globale
- indicateurs conformes
- indicateurs partiellement conformes
- indicateurs non conformes
- indicateurs impossibles à apprécier en l'état (avec les vérifications nécessaires)
- indicateurs non documentés ou non démontrés

### C. Tableau de synthèse
| Indicateur | Niveau observé | Points forts | Fragilités | Action prioritaire |

### D. Top priorités avant audit
- 5 à 10 actions classées par urgence

### E. Conseils méthodologiques
- documents à fiabiliser
- preuves à mieux structurer
- formulations à retravailler
- éléments à préparer pour l'entretien d'audit

### F. Conclusion
- conclusion prudente et motivée sur le niveau de préparation de l'organisme pour l'audit réel

Règles impératives :
- n'invente aucune preuve
- ne considère pas un document nommé comme nécessairement conforme
- ne présente pas une pratique supposée comme démontrée
- signale clairement les limites de l'analyse
- adapte tes attentes au périmètre réellement applicable
- reste rigoureux sans être excessivement formaliste

Références à mobiliser :
- Référentiel National Qualité v10 : décret n° 2026-728 du 1er août 2026 (https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000054608509)
- arrêté du 28 octobre 2026 relatif aux modalités d'audit et d'accréditation (https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000055041105)
- guide de lecture V10 de la DGEFP, à vérifier dans sa dernière version
- guides France Compétences applicables
- cahiers des charges et doctrines d'audit Qualiopi
- FAQ DGEFP et FAQ France Compétences si pertinentes
- exigences liées au type d'action concerné

Commence par :
1. rappeler le cadre de l'audit blanc et la version du référentiel applicable
2. me demander les éléments de contexte manquants
3. confirmer le périmètre applicable
4. ouvrir l'indicateur 1 avec les premières questions
