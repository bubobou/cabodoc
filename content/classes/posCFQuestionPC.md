+++
title = "posCFQuestionPC"
description = "container de question pour la vue positionnement"
author = "bek"
date = "2021-03-18"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [PanelContainer](../PanelContainer)

## Description

container de question pour la vue positionnement

## Property Descriptions

### boutonComp

```gdscript
var boutonComp
```

### labelId

```gdscript
var labelId
```

### labelText

```gdscript
var labelText
```

### questHbox

```gdscript
var questHbox
```

### dataQuest

```gdscript
var dataQuest: Dictionary
```

dictionnnaire stockant les données de la question (id, liste de compétences)

## Method Descriptions

### eleve\_selected

```gdscript
func eleve_selected(data)
```

transmission des niveau des compétences de la question aux boutons "boutonComp"

## Signals

- signal eleveUpdate(): signal émis lorsqu'un élève a été sélectionné
