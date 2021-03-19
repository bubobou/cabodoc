+++
title = "positionModel"
description = "data access Object à la table POSITIONNEMENT"
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access Object à la table POSITIONNEMENT

## Method Descriptions

### getEleveList

```gdscript
func getEleveList(idEvaluation)
```

récupère la liste des élèves concernés par l'évaluation

### transformEleve

```gdscript
func transformEleve(eleveArray)
```

inutile ?

### getQuestionWithCompetenceByGrilleId

```gdscript
func getQuestionWithCompetenceByGrilleId(idGrille)
```

récupère toutes les questions de la grille donnée en paramètre

### transformQuestionCompetence

```gdscript
func transformQuestionCompetence(qstWithCmpArray)
```

contruit la structure de donnée de la rubrique question

### initializeQstDic

```gdscript
func initializeQstDic(qstDic, qstId)
```

intialise la structure de donnée "question"

### updatePosition

```gdscript
func updatePosition(id_eleve, id_evaluation, id_question, id_competence, position)
```

affectation d'une nouvelle valeur de position pour la compétence évaluée

### getPosition

```gdscript
func getPosition(id_eleve, id_evaluation, id_question, id_competence)
```

récupération de la valeur d'une position correspondant à une ligne de la table POSITIONNEMENT

### getGrilleNameById

```gdscript
func getGrilleNameById(idGrille)
```

