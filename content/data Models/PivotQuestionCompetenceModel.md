+++
title = "PivotQuestionCompetenceModel"
description = "data access object de la table QUESTION_COMPETENCE_PIVOT"
author = "bb"
date = "2021-03-07"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access object de la table QUESTION_COMPETENCE_PIVOT

## Method Descriptions

### linkQuestionToManyCompetence

```gdscript
func linkQuestionToManyCompetence(idQuestion, competenceArray)
```

lie une question à plusieurs compétences

### insertManyRaws

```gdscript
func insertManyRaws(rawsArray)
```

insère plusieurs lignes dans la table QUESTION_COMPETENCE_PIVOT

### flashLinkByQuestionId

```gdscript
func flashLinkByQuestionId(idQuestion)
```

supprime tous les liens de compétences de QuestionId donné en argument

### prepareRawByQuestion

```gdscript
func prepareRawByQuestion(idQuestion, competenceArray)
```

prépare plusieurs lignes à insérer dans la table QUESTION_COMPETENCE_PIVOT