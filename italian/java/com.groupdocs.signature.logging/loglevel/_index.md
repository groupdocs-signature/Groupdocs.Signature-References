---
title: "LogLevel"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Specifica i tipi di livello di log disponibili."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Specifica i tipi di livello di log disponibili.
Questa enumerazione può essere usata come flag per impostare diversi valori possibili come bit abilitati
Esempio: LogLevel.Error \| LogLevel.Warning o LogLevel.Error \| LogLevel.Trace

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [None](#None) | Nessuna limitazione di logging, tutte le informazioni saranno registrate da traccia, avviso a errori |
|
|  | [Error](#Error) | Nessuna limitazione di logging, tutte le informazioni saranno registrate da traccia, avviso a errori |
|
|  | [Warning](#Warning) | Stesso livello di All, tutti i messaggi incluso il livello Trace saranno registrati |
|
|  | [Trace](#Trace) | Il livello di logging per includere i messaggi dal livello Avviso al livello Errore |
|
|  | [All](#All) | Tutti gli eventi di livello Log (Errore, Avviso, Traccia) saranno inclusi nel logging |
|
### None {#None}
```
public static final int None
```


Nessuna limitazione di logging, tutte le informazioni saranno registrate da traccia, avviso a errori


### Error {#Error}
```
public static final int Error
```


Nessuna limitazione di logging, tutte le informazioni saranno registrate da traccia, avviso a errori


### Warning {#Warning}
```
public static final int Warning
```


Stesso livello di All, tutti i messaggi incluso il livello Trace saranno registrati


### Trace {#Trace}
```
public static final int Trace
```


Il livello di logging per includere i messaggi dal livello Avviso al livello Errore


### All {#All}
```
public static final int All
```


Tutti gli eventi di livello Log (Errore, Avviso, Traccia) saranno inclusi nel logging


