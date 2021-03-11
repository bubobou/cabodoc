+++
title = "PivotGrilleQuestionModel"
description = "data access model de la table GRILLE_QUESTION_PIVOT"
author = "bek"
date = "2021-03-11"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access model de la table GRILLE_QUESTION_PIVOT

## Method Descriptions

### getQuestionWithCompetenceByGrilleId

```gdscript
func getQuestionWithCompetenceByGrilleId(idGrille)
```

récupère toutes les questions de la grille donné en paramètre

### transformQuestionCompetence

```gdscript
func transformQuestionCompetence(qstWithCmpArray)
```

construit la structure de donnée la rubrique question

### initializeQstDic

```gdscript
func initializeQstDic(qstDic, qstId)
```

initialise la structure de donnée "question"

### getGrilleReferentieLinked

```gdscript
func getGrilleReferentieLinked()
```

récupère les données qui lient la grille aux référentiels, en passant par les questions

### linkGrilleToManyQuestion

```gdscript
func linkGrilleToManyQuestion(idGrille, questionIdArray)
```

### insertManyRaws

```gdscript
func insertManyRaws(rawsArray)
```

### prepareRawByGrille

```gdscript
func prepareRawByGrille(idGrille, questionIdArray)
```

prépare les lignes pour insertion dans la table GRILLE_QUESTION_PIVOT

### flashLinkByGrilleId

```gdscript
func flashLinkByGrilleId(idGrille)
```

