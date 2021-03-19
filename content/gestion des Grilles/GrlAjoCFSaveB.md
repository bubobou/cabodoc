+++
title = "GrlAjoCFSaveB"
description = "gère le bouton \"Enregistrer grille\""
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [Button](../Button)

## Description

gère le bouton "Enregistrer grille"

## Property Descriptions

### grilleModel

```gdscript
var grilleModel
```

instance du data object acces grilleModel

### formNode

```gdscript
var formNode
```

noeud du formulaire grlAjoCForm-VBC

### grilleForm

```gdscript
var grilleForm
```

## Method Descriptions

### getGrilleDic

```gdscript
func getGrilleDic()
```

collecte la structure de donnée grille à partir du formulaire de grille

### getGrilleQuestions

```gdscript
func getGrilleQuestions()
```

récupère un tableau des questions à partir du formulaire grille

### getQuestionDic

```gdscript
func getQuestionDic(questionNode)
```

récupère la structure de donnée d'une question

### getCompetenceIds

```gdscript
func getCompetenceIds(questionNode)
```

récupère les compétences d'une question

### getIdCompetence

```gdscript
func getIdCompetence(competenceRaw)
```

récupère et valide competenceId

### getQuestionDomainlId

```gdscript
func getQuestionDomainlId(questionNode)
```

récupère et valide le DomainId d'une question

### getQuestionReferentielId

```gdscript
func getQuestionReferentielId(questionNode)
```

récupère et valide le ReferentielId d'une question

### getQuestionText

```gdscript
func getQuestionText(questionNode)
```

récupère et valide l'intitulé de la question

### getQuestionId

```gdscript
func getQuestionId(questionNode)
```

récupère QuestionId

### getGrilleId

```gdscript
func getGrilleId()
```

récupère GrilleId

### getGrilleName

```gdscript
func getGrilleName()
```

récupère et valide le nom de la grille