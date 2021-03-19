+++
title = "posiPC"
description = "gère la page de positionnement des élèves"
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [PanelContainer](../PanelContainer)

## Description

gère la page de positionnement des élèves

## Property Descriptions

### questionRow

```gdscript
var questionRow
```

la scene du container de question

### positionModel

```gdscript
var positionModel
```

instanciation du modèle d'accès à la table POSITIONNEMENT

### elevePicker

```gdscript
var elevePicker
```

### questionsContainer

```gdscript
var questionsContainer
```

### eleveName

```gdscript
var eleveName
```

### posiTitle

```gdscript
var posiTitle
```

### selectedEleveId

```gdscript
var selectedEleveId: int
```

variable contenant l'ID de l'élève sélectionné

### idEvaluation

```gdscript
var idEvaluation: String
```

variable de type String contenant l'ID de l'évaluation

### idGrille

```gdscript
var idGrille
```

## Method Descriptions

### elevePicker\_init

```gdscript
func elevePicker_init(evaluation_id)
```

initialise le popup de sélection avec nom de l'élève

### questionList\_init

```gdscript
func questionList_init(grille_id)
```

instanciation, connexion et ajout des containers "question"

### on\_niveau\_update

```gdscript
func on_niveau_update(idQuest, idComp, posValue)
```

mise à jour du niveau d'une compétence, déclenchée par le signal "niveauChange" d'un bouton "boutonComp"

### on\_eleve\_selected

```gdscript
func on_eleve_selected(id)
```

mise à jour du nom et envoi d'un signal aux container "question" avec le positionnement de l'élève

## Signals

- signal eleveSelect(data): signal émis lors de la sélection d'un élève
