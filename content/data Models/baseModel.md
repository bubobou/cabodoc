+++
title = "baseModel"
description = "modèle de data access object\ncategory: Model"
author = "bb"
date = "2021-03-07"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [Data](../Data) < [Node](../Node)

## Description

modèle de data access object
category: Model

## Constants Descriptions

### SQLite

```gdscript
const SQLite: NativeScript = preload("res://addons/godot-sqlite/bin/gdsqlite.gdns")
```

## Property Descriptions

### db

```gdscript
var db
```

### dbName

```gdscript
var dbName: String
```

### jsonName

```gdscript
var jsonName: String
```

## Method Descriptions

### cprint

```gdscript
func cprint(text: String) -> void
```

### copy\_data\_to\_user

```gdscript
func copy_data_to_user() -> void
```

copier les données vers le répertoire data

### connectDb

```gdscript
func connectDb()
```

connection à la base de données

### getLastInsertedId

```gdscript
func getLastInsertedId(tableName)
```

obtenir le dernier Id inserer dans une table de la base de donnée, donné en paramètre

## Signals

- signal output_received(text): 
