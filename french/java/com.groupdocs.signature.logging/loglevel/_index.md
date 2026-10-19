---
title: "LogLevel"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Spécifie les types de niveaux de journalisation disponibles."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Spécifie les types de niveaux de journalisation disponibles.
Cette énumération peut être utilisée comme indicateurs pour définir plusieurs valeurs possibles comme bits activés
Exemple : LogLevel.Error \| LogLevel.Warning ou LogLevel.Error \| LogLevel.Trace

## Champs

| Champ | Description |
| --- | --- |
|  | [None](#None) | Aucune limitation de journalisation, toutes les informations seront enregistrées de la trace, de l'avertissement aux erreurs |
|
|  | [Error](#Error) | Aucune limitation de journalisation, toutes les informations seront enregistrées de la trace, de l'avertissement aux erreurs |
|
|  | [Warning](#Warning) | Identique au niveau Tout, tous les messages, y compris le niveau Trace, seront enregistrés |
|
|  | [Trace](#Trace) | Le niveau de journalisation pour inclure les messages du niveau Avertissement au niveau Erreur |
|
|  | [All](#All) | Tous les événements de niveau de journal (Erreur, Avertissement, Trace) seront inclus dans la journalisation |
|
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


Identique au niveau Tout, tous les messages, y compris le niveau Trace, seront enregistrés


### Trace {#Trace}
```
public static final int Trace
```


Le niveau de journalisation pour inclure les messages du niveau Avertissement au niveau Erreur


### All {#All}
```
public static final int All
```


Tous les événements de niveau de journal (Erreur, Avertissement, Trace) seront inclus dans la journalisation


