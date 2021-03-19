+++
title = "posCFCompB"
description = "bouton d'évaluation des compétence"
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [Button](../Button)

## Description

bouton d'évaluation des compétence

## Property Descriptions

### sceneNode

```gdscript
var sceneNode
```

récupération du noeud de la scène "évaluation"

### positionModel

```gdscript
var positionModel
```

instanciation du modèle d'accès à la table POSITIONNEMENT

### new\_style

```gdscript
var new_style
```

intanciation d'un stylebox pour l'appliquer au bouton

### idEval

```gdscript
var idEval: String
```

identifiant de l'évaluation (String)

### posValue

```gdscript
var posValue: int
```

positionnement (niveau) de la compétence

### idQuest

```gdscript
var idQuest: int
```

identifiant de la question

### idComp

```gdscript
var idComp: int
```

identifiant de la compétence

### couleurs

```gdscript
var couleurs: Array
```

le tableau des couleurs attibuées au bouton selon le positionnement de la compétence

## Method Descriptions

### color\_update

```gdscript
func color_update()
```

modification de la couleur du bouton en fonction du niveau

### on\_received\_data

```gdscript
func on_received_data(idEleve)
```

actualisation lorsqu'une donnée est reçue (sélection d'un élève)

## Signals

- signal posChange(idQuest, idComp, posValue): signal pour remonter le niveau de la compétence
