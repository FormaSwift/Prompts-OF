# FORMDEV

## Objet du dossier

Ce dossier regroupe des prompts spécialisés pour analyser les exports Formdev avec une logique de pilotage, de contrôle et d'aide à la décision.

L'objectif n'est pas de refaire les tableaux de bord déjà disponibles dans Formdev.

L'objectif est d'aller plus loin que les vues natives pour :
- détecter des écarts et des anomalies ;
- rapprocher plusieurs exports entre eux ;
- fiabiliser la lecture DAF, comptable, administrative, commerciale ou qualité ;
- prioriser les actions ;
- préparer les échanges avec le comptable, la direction, l'administratif, le commercial ou la qualité ;
- transformer les exports en décisions concrètes.

## Principe général

Les prompts FORMDEV ne sont pas conçus pour "résumer un tableau".

Ils sont conçus pour répondre à des questions métier du type :
- que dois-je vérifier ?
- qu'est-ce qui dérive ?
- où l'argent se bloque-t-il ?
- quels dossiers sont à risque ?
- quelles sessions fragilisent le pilotage ?
- quelles créances faut-il relancer en premier ?
- quels programmes montrent des signaux faibles qualité ?
- quels écarts dois-je revoir avec le comptable ?

## Où récupérer les exports dans Formdev

### 1. Exports "Tableaux de bord"
À extraire depuis :
- onglet Pilotage
- puis Tableaux de bord

C'est le cas notamment pour :
- Devis - Commercial
- Signatures numériques - Commercial
- CA par session et organisation - Commercial
- Factures - Direction
- Lignes de factures - Direction
- Situation des dossiers - Direction
- Apprenants par session - Direction
- CA par intervenant - Production
- Rapport par programme - Qualité
- Programmes - Qualité

### 2. Export des sessions
À extraire depuis :
- onglet Sessions

### 3. Export des organisations
À extraire depuis :
- onglet Organisations

### 4. Exports comptables
À extraire depuis :
- onglet Finance

C'est le cas notamment pour :
- Journal des ventes
- Journal des encaissements

## Règle clé d'utilisation

Un prompt FORMDEV utile doit partir :
- d'un besoin de pilotage précis ;
- de plusieurs exports cohérents entre eux si nécessaire ;
- d'une demande orientée décision.

Exemple de mauvaise demande :
- "Analyse ce tableau"

Exemple de bonne demande :
- "Analyse ces exports comme un DAF d'organisme de formation. Je veux repérer les factures d'avance à surveiller, les FAE probables, les dossiers incohérents et les points à revoir avec le comptable."

## Confidentialité et anonymisation

Les exports Formdev peuvent contenir des données sensibles.

Par défaut, il est recommandé de :
- ne pas afficher inutilement les noms et prénoms des apprenants, signataires ou contacts ;
- ne pas reproduire les coordonnées personnelles ;
- anonymiser les personnes physiques lorsque leur identité n'est pas utile à la décision ;
- privilégier les identifiants de type :
  - numéro de dossier
  - numéro de facture
  - analytique
  - session
  - programme
- conserver les noms des organisations seulement si cela change réellement l'analyse ou l'action à mener.

Règle pratique :
- personnes physiques = anonymisation par défaut
- organisations = conservation si utile au pilotage, sinon anonymisation possible

## Ce que les prompts FORMDEV doivent apporter

Les prompts doivent apporter plus que Formdev lui-même.

Ils doivent permettre :
- une lecture hiérarchisée ;
- une lecture comparative ;
- une lecture prudente des causes possibles ;
- une priorisation des actions ;
- un plan de contrôle ;
- une aide à la décision.

Ils doivent produire, selon les cas :
- une synthèse dirigeant ;
- un tableau des anomalies ;
- une lecture des écarts ;
- des hypothèses prudentes ;
- des priorités de vérification ;
- un plan d'action.

## Mode d'emploi conseillé

### Étape 1 - Identifier le bon besoin
Avant de lancer un prompt, clarifier le besoin :
- DAF / compta
- recouvrement
- pré-clôture
- sessions à risque
- rentabilité
- commercial
- qualité
- direction

### Étape 2 - Extraire les bons fichiers
Ne pas joindre "tout ce qu'on a".

Joindre uniquement les exports utiles au besoin posé.

### Étape 3 - Formuler une vraie demande métier
Une bonne demande doit dire :
- le rôle attendu : DAF, direction, commercial, qualité, etc.
- l'objectif : contrôler, rapprocher, prioriser, détecter, arbitrer
- le niveau de détail attendu
- le type de sortie souhaité

### Étape 4 - Attendre une sortie exploitable
La sortie attendue n'est pas un commentaire vague.

La sortie attendue doit être :
- structurée ;
- prudente ;
- actionnable ;
- orientée vérification ou décision.

## Gabarit conseillé pour tous les prompts FORMDEV

Chaque prompt de ce dossier devrait comporter les sections suivantes :

### Fichiers à joindre
Exemple :
- Journal des ventes.csv
- Journal des encaissements.csv
- Tableaux de bord - Factures - Direction
- Tableaux de bord - Situation des dossiers - Direction

### Demande conseillée
Exemple :
- Analyse ces exports comme un DAF d'organisme de formation.
- Je veux identifier les écarts entre vendu, facturé et encaissé.
- Je veux repérer les anomalies à vérifier, les créances prioritaires et les points à revoir avec le comptable.

### Sortie attendue
Exemple :
- synthèse DAF
- tableau des anomalies
- priorités de vérification
- hypothèses prudentes
- plan d'action

## Axes d'analyse à plus fort ROI

### 1. DAF / compta
Objectif :
- sécuriser le cut-off ;
- fiabiliser la lecture comptable ;
- préparer les échanges avec le comptable.

Analyses typiques :
- contrôle des facturés d'avance ;
- repérage des factures à établir probables ;
- rapprochement ventes / factures / encaissements ;
- vérification des comptes comptables ;
- pré-clôture mensuelle ;
- priorisation des créances.

Exports souvent utiles :
- Journal des ventes
- Journal des encaissements
- Factures - Direction
- Lignes de factures - Direction
- Situation des dossiers - Direction
- Apprenants par session - Direction
- sessions_export
- organisations_export

### 2. Direction / pilotage
Objectif :
- savoir rapidement quoi regarder en priorité.

Analyses typiques :
- sessions à risque ;
- écarts entre réel pédagogique et lecture économique ;
- synthèse de pilotage hebdomadaire ou mensuelle ;
- dossiers sensibles.

Exports souvent utiles :
- Apprenants par session - Direction
- sessions_export
- Situation des dossiers - Direction
- Factures - Direction
- Journal des ventes
- Journal des encaissements

### 3. Commercial
Objectif :
- lire le pipe réel ;
- relancer mieux ;
- comprendre où le tunnel se bloque.

Analyses typiques :
- diagnostic du tunnel commercial ;
- priorisation des devis à relancer ;
- lecture par produit ;
- lecture par organisation ;
- lecture par utilisateur ;
- analyse des signatures numériques comme point de friction.

Exports souvent utiles :
- Devis - Commercial
- Signatures numériques - Commercial
- CA par session et organisation - Commercial
- organisations_export

### 4. Production / rentabilité
Objectif :
- repérer les sessions fragiles ;
- approcher la rentabilité réelle.

Analyses typiques :
- sessions à risque économique ;
- rentabilité par session ;
- rentabilité par programme ;
- rentabilité par intervenant ;
- écarts entre charge pédagogique, heures, CA et facturation.

Exports souvent utiles :
- Apprenants par session - Direction
- sessions_export
- CA par intervenant - Production
- Lignes de factures - Direction
- Journal des ventes

### 5. Qualité
Objectif :
- utiliser la qualité comme levier de pilotage, pas seulement comme preuve.

Analyses typiques :
- diagnostic qualité par programme ;
- pilotage des questionnaires ;
- détection de campagnes dormantes ;
- signaux faibles de satisfaction ;
- priorisation des actions qualité.

Exports souvent utiles :
- campagne_de_questionnaires_export
- Rapport par programme - Qualité
- Programmes - Qualité
- sessions_export

## Bonnes pratiques

- Toujours raisonner en "signal", "hypothèse", "anomalie probable" ou "contrôle à lancer", pas en vérité comptable définitive.
- Ne pas confondre un export de gestion avec la comptabilité générale.
- Croiser plusieurs exports quand on veut sécuriser une lecture.
- Prioriser les montants significatifs et les écarts structurants.
- Éviter les prompts trop génériques.
- Toujours viser une action ou une décision.

## Promesse de la catégorie FORMDEV

La valeur de cette catégorie n'est pas :
- de refaire un tableau de bord ;
- de résumer un export.

La valeur de cette catégorie est :
- de gagner du temps ;
- d'automatiser l'analyse ;
- d'améliorer la fiabilité ;
- d'orienter les décisions ;
- de mieux piloter l'organisme de formation à partir des données Formdev.
