+++
title = "GlobalHelper"
description = "fonctions communes utilisés partout dans tout le code"
author = "bek"
date = "2021-03-19"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [Node](../Node)

## Description

fonctions communes utilisés partout dans tout le code

## Constants Descriptions

### HOURS

```gdscript
const HOURS: Array = ["00","01","02","03","04","05","06","07","08","09","10","11","12","13","14","15","16","17","18","19","20","21","22","23"]
```

### MINUTES

```gdscript
const MINUTES: Array = ["00","05","10","15","20","25","30","35","40","45","50","55"]
```

## Property Descriptions

### domaineModel

```gdscript
var domaineModel
```

### competenceModel

```gdscript
var competenceModel
```

### referentielModel

```gdscript
var referentielModel
```

## Method Descriptions

### fillQuestionText

```gdscript
func fillQuestionText(qstText, questionNode)
```

### mergeDic

```gdscript
func mergeDic(dicOne, dicTwo)
```

ajoute le dictionnaire 2 donné en paramètre au dictionnaire 1 donné en paramètre

### prepareInString

```gdscript
func prepareInString(valuesArray)
```

prépare une chaîne de caractères SQL du IN qui contient une liste de valeurs donnés en paramètre

### fillReferentielOptionButton

```gdscript
func fillReferentielOptionButton(refOptionsNode, idRef: int = 0)
```

remplit la selectbox intitulé "Référentiel" depuis la base de donnée et sélectionne le réferentiel passé en argument

### getAllReferentiel

```gdscript
func getAllReferentiel()
```

### fillDomainAndCompetance

```gdscript
func fillDomainAndCompetance(refId, domainOptionsNode, competenceOptionsNode, domainId: int = 0, competenceIdArray: Array = 0)
```

remplit les selectbox Domaines et Compétences à partir de la base de donnée

### getDomaineByRefId

```gdscript
func getDomaineByRefId(refId)
```

### fillManyCompetence

```gdscript
func fillManyCompetence(idDomain, multiCompetenceNode, competenceIdArray: Array = 0)
```

remplit les selectbox intitulés "Compétences" depuis la base de donnée et sélectionne les compétences passés en argument

### getCompetenceArrayByDomainId

```gdscript
func getCompetenceArrayByDomainId(idDomain)
```

### createMultiCompetence

```gdscript
func createMultiCompetence(parentNode, childNumber)
```

duplique la scène qui contient une ligne de compétence = selectbox + button (+/-)

### removeAllChildren

```gdscript
func removeAllChildren(nodeObject)
```

supprime les enfants d'un noeud donné

### fillCompetanceOptionButton

```gdscript
func fillCompetanceOptionButton(competanceArray, competenceOptionsNode, competenceId: int = 0)
```

remplit la selectbox intitulé "Compétences" depuis la base de donnée et sélectionne la compétence passée en argument

### fillDomaineOptionButton

```gdscript
func fillDomaineOptionButton(domaineArray, domainOptionsNode, domainId: int = 0)
```

remplit la selectbox intitulé "Domaine" depuis la base de donnée et sélectionne le domaine passé en argument

### setChildrenNumber

```gdscript
func setChildrenNumber(parentNode)
```

numérote toutes les questions du formulaire de création/modification d'une grille

### setQuestionNumber

```gdscript
func setQuestionNumber(node, number)
```

attribue un numéro à une question du formulaire de création/modification d'une grille

### displayForm

```gdscript
func displayForm(formData)
```

met en couleur les champs requis d'un formulaire

### highlightWrongField

```gdscript
func highlightWrongField(pathArray)
```

met en couleur les champs erronnés

### addRedBorder

```gdscript
func addRedBorder(nodeObject)
```

ajoute une bordure rouge

### addRedBorderToNormalStyle

```gdscript
func addRedBorderToNormalStyle(nodeObject)
```

ajoute une bordure rouge au style normal

### prepareText

```gdscript
func prepareText(textString, maxChar: int = 0)
```

### duplicateFirstChild

```gdscript
func duplicateFirstChild(size, parentNode, hideZero: bool = true)
```

multiplie ou cache le premier noeud enfant du noeud parent donné en argument, un nombre de fois donné en argument

### pluckArrayOfDicByColumn

```gdscript
func pluckArrayOfDicByColumn(dicArray, fieldName)
```

### fillOptionButton

```gdscript
func fillOptionButton(optionButtonNode: OptionButton, labelArray: Array, idArray: Array, toSelectndex: int = 0)
```

