+++
title = "QuestionModel"
description = "data access object de la table QUESTION"
author = "bek"
date = "2021-03-11"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access object de la table QUESTION

## Method Descriptions

### saveManyQuestion

```gdscript
func saveManyQuestion(questionArray, idGrille)
```

sauvegarde plusieurs questions et les lient à la grille passée en argument

### saveQuestion

```gdscript
func saveQuestion(questionDic)
```

crée et met à jour une question

### updateQuestion

```gdscript
func updateQuestion(questionDic)
```

### updateQuestionRaw

```gdscript
func updateQuestionRaw(questionDic)
```

### createQuestion

```gdscript
func createQuestion(questionDic)
```

crée et lie une question aux compétences associées

### insertQuestionRaw

```gdscript
func insertQuestionRaw(questionDic)
```

insère une nouvelle ligne dans la table QUESTION