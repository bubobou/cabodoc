+++
title = "eleveModel"
description = "data access object de la table ELEVE"
author = "bb"
date = "2021-03-07"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [baseModel](../baseModel) < [Data](../Data) < [Node](../Node)

## Description

data access object de la table ELEVE

## Method Descriptions

### getEleveWithGroups

```gdscript
func getEleveWithGroups()
```

### getEleveWithoutGroupe

```gdscript
func getEleveWithoutGroupe(idsHavingGroupe)
```

sélectionner dans la table ELEVE, ceux qui ne sont pas affectés à un groupe; retourner un dictionnaire {idEleve : {Name , Groupes}}

### getEleveThatHasGroupe

```gdscript
func getEleveThatHasGroupe()
```

effectuer une requête sur la table ELEVE_GROUPE_PIVOT pour récupérer les élèves affectés à un groupe et retourner un dictionnaire contenant les groupes affectés à chaque élève via transformEleveGroups(queryResult)`.

### transformEleve

```gdscript
func transformEleve(eleveArray)
```

### transformEleveGroups

```gdscript
func transformEleveGroups(queryResult)
```

retourner un dictionnaire {idEleve : {Name , Groupes}} avec Name = Nom Prenom et Groupes = liste des groupes de l'élève

### saveEleve

```gdscript
func saveEleve(eleveDic)
```

### insertEleve

```gdscript
func insertEleve(eleveDic)
```

### updateEleve

```gdscript
func updateEleve(eleveDic)
```

### createNewEleve

```gdscript
func createNewEleve(eleveDic)
```

### getEleveById

```gdscript
func getEleveById(idEleve)
```

### deleteEleve

```gdscript
func deleteEleve(idEleve)
```

### eraseEleveRaw

```gdscript
func eraseEleveRaw(idEleve)
```

