+++
title = "baseModel"
description = "modèle de data access object"
author = "bek"
date = "2021-03-11"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** [Data](../Data) < [Node](../Node)

## Description

modèle de data access object

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

### connectDb

```gdscript
func connectDb()
```

### getLastInsertedId

```gdscript
func getLastInsertedId(tableName)
```

obtenir le dernier Id inseré dans une table de la base de données, donnée en paramètre

## Signals

- signal output_received(text): 
