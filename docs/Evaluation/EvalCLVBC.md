+++
title = "EvalCLVBC"
description = "gère la liste des évaluations"
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [VBoxContainer](../VBoxContainer)

## Description

gère la liste des évaluations

## Property Descriptions

### evaluationModel

```gdscript
var evaluationModel
```

### grilleModel

```gdscript
var grilleModel
```

### groupeModel

```gdscript
var groupeModel
```

## Method Descriptions

### fillEvaluationRaws

```gdscript
func fillEvaluationRaws(evalDic)
```

remplit les lignes de la liste de grilles

### fillGroupeName

```gdscript
func fillGroupeName(rawNode, groupeText)
```

remplit la colonne niveau de la ligne liste des grilles

### fillGrilleName

```gdscript
func fillGrilleName(rawNode, grilleText)
```

remplit la colonne discipline de la ligne liste des grilles

### fillEvalDate

```gdscript
func fillEvalDate(rawNode, dateText)
```

remplit le nom de la grille

### fillButtonText

```gdscript
func fillButtonText(buttonNode, buttonText)
```

ajoute un texte à un bouton selon la longueur du texte

### fillEvaluationId

```gdscript
func fillEvaluationId(rawNode, idText)
```

remplit grilleId