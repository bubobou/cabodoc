+++
title = "PivotGrilleQuestionModel"
description = "data access model de la table GRILLE_QUESTION_PIVOT"
author = "bb"
date = "2021-03-07"
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

contruit la struction de donnée la rubrique question

### initializeQstDic

```gdscript
func initializeQstDic(qstDic, qstId)
```

intialise la structure de donnée "question"

### getGrilleReferentieLinked

```gdscript
func getGrilleReferentieLinked()
```

récupère les données qui lient la grille aux réferentiels, en passant par les questions

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

### flashLinkByGrilleId

```gdscript
func flashLinkByGrilleId(idGrille)
```

