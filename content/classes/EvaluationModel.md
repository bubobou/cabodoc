+++
title = "EvaluationModel"
description = "data access object de la table EVALUATION"
author = "bek"
date = "2021-03-18"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access object de la table EVALUATION

## Method Descriptions

### getEvaluationById

```gdscript
func getEvaluationById(idEvaluation)
```

### getGrilleEvalById

```gdscript
func getGrilleEvalById(idGrille)
```

### getGroupeEvalById

```gdscript
func getGroupeEvalById(idGroupe)
```

### getEvaluationList

```gdscript
func getEvaluationList()
```

récupère la liste des évaluations

### createEvaluation

```gdscript
func createEvaluation(evaluationDic)
```

crée une nouvelle évaluation par insertion dans la table

### createNewPositionnement

```gdscript
func createNewPositionnement(idEvaluation)
```

crée les entrées dans la table POSITION d'après les données de l'évaluation