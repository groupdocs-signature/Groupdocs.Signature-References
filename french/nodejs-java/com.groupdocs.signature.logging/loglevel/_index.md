---
title: "LogLevel"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Spécifie les types de niveaux de journalisation disponibles."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Spécifie les types de niveaux de journalisation disponibles. Cette énumération peut être utilisée comme indicateurs pour définir plusieurs valeurs possibles comme bits activés Exemple : LogLevel.Error | LogLevel.Warning ou LogLevel.Error | LogLevel.Trace
## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Aucune limitation de journalisation, toutes les informations seront enregistrées de la trace, de l'avertissement aux erreurs |
| [Error](#Error) | Aucune limitation de journalisation, toutes les informations seront enregistrées de la trace, de l'avertissement aux erreurs |
| [Warning](#Warning) | Comme le niveau All, tous les messages, y compris le niveau Trace, seront enregistrés |
| [Trace](#Trace) | Le niveau de journalisation pour inclure les messages du niveau Warning au niveau Error |
| [All](#All) | Tous les événements du niveau Log (Error, Warning, Trace) seront inclus dans la journalisation |
### None {#None}
```
public static final int None
```


Aucune limitation de journalisation, toutes les informations seront enregistrées de la trace, de l'avertissement aux erreurs

### Error {#Error}
```
public static final int Error
```


Aucune limitation de journalisation, toutes les informations seront enregistrées de la trace, de l'avertissement aux erreurs

### Warning {#Warning}
```
public static final int Warning
```


Comme le niveau All, tous les messages, y compris le niveau Trace, seront enregistrés

### Trace {#Trace}
```
public static final int Trace
```


Le niveau de journalisation pour inclure les messages du niveau Warning au niveau Error

### All {#All}
```
public static final int All
```


Tous les événements du niveau Log (Error, Warning, Trace) seront inclus dans la journalisation

