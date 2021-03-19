+++
title = "GrlAjoPC"
description = "gère la page d'ajout et de modification d'une grille"
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [PanelContainer](../PanelContainer)

## Description

gère la page d'ajout et de modification d'une grille

## Property Descriptions

### grilleModel

```gdscript
var grilleModel
```

### pivotGrlQstModel

```gdscript
var pivotGrlQstModel
```

## Method Descriptions

### fillGrilleForm

```gdscript
func fillGrilleForm(idGrille)
```

remplit le formulaire de modification d'une grille donnée en argument

### removeLoadedQuestionNode

```gdscript
func removeLoadedQuestionNode(qstFormNode)
```

supprime le formulaire d'ajout de question

### fillQuestions

```gdscript
func fillQuestions(questionArray, qstFormNode)
```

remplit les questions dans le formulaire récupérée de la base de donnée

### fillQuestionId

```gdscript
func fillQuestionId(qstId, questionNode)
```

remplit QuestionId dans un champ caché

### fillGrilleName

```gdscript
func fillGrilleName(grilleName)
```

remplit le champ nom de la grille passé en argument

### fillIdGrille

```gdscript
func fillIdGrille(idGrille)
```

remplit le champ idGrille

### editPageTitle

```gdscript
func editPageTitle()
```

change le titre de la page de création de grille en titre de modification de grille

### displayDeleteButton

```gdscript
func displayDeleteButton()
```

display le bouton "supprimer grille"