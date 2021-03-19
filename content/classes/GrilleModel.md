+++
title = "GrilleModel"
description = "data access object de la table GRILLE"
author = "bek"
date = "2021-03-18"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access object de la table GRILLE

## Method Descriptions

### deleteGrille

```gdscript
func deleteGrille(idGrille)
```

### deleteGrilleQuestions

```gdscript
func deleteGrilleQuestions(idGrille)
```

### deleteGrilleRaw

```gdscript
func deleteGrilleRaw(idGrille)
```

### getGrilleById

```gdscript
func getGrilleById(idGrille)
```

récupère le nom de la grille par idGrille passé en argument

### getGrilleList

```gdscript
func getGrilleList()
```

récupère la liste des grilles avec leur référentiel associé

### getGrilleWithoutQuestion

```gdscript
func getGrilleWithoutQuestion(grillIdWithQuestion)
```

récupère les grilles qui n'ont pas de questions

### transformGrille

```gdscript
func transformGrille(grilleArray)
```

### prepareGrilleList

```gdscript
func prepareGrilleList(grilleRefLinkArray)
```

construit la liste de grille à partir des données du résultat de la requête qui lie la grille aux référentiels

### insertUniqueValueInArray

```gdscript
func insertUniqueValueInArray(desArray, value)
```

insère une valeur dans un tableau seulement si celle-ci n'est déjà pas présente

### initializeGrlRefRaw

```gdscript
func initializeGrlRefRaw(dic, field)
```

initialise le champ passé en argument, du dictionnaire passé en argument avec la structure ligne de la liste de grille

### nvEtDscToString

```gdscript
func nvEtDscToString(grilleList)
```

transforme les tableaux niveaux et disciplines en chaîne de caractère pour chaque élément dans la liste des grilles donnés en paramètre

### arrayToString

```gdscript
func arrayToString(givenArray)
```

transforme les valeurs d'un tableau en une chaîne de caractère séparé par une virgule

### saveGrille

```gdscript
func saveGrille(grilleDic)
```

crée ou modifie la grille donné en paramètre

### updateGrille

```gdscript
func updateGrille(grilleDic)
```

### updateGrilleRaw

```gdscript
func updateGrilleRaw(grilleDic)
```

### createGrille

```gdscript
func createGrille(grilleDic)
```

crée une nouvelle grille et relie les questions et les compétences passé en argument

### insertGrilleRaw

```gdscript
func insertGrilleRaw(grilleDic)
```

insère une nouvelle ligne dans la table GRILLE de la base de donnée