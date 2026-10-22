---
title: "LogLevel"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Specifica i tipi di livello di log disponibili."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Specifica i tipi di livello di log disponibili. Questa enumerazione può essere usata come flag per impostare diversi valori possibili come bit abilitati. Esempio: LogLevel.Error | LogLevel.Warning o LogLevel.Error | LogLevel.Trace
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Nessuna limitazione di logging, tutte le informazioni verranno registrate dalla traccia, avviso agli errori |
| [Error](#Error) | Nessuna limitazione di logging, tutte le informazioni verranno registrate dalla traccia, avviso agli errori |
| [Warning](#Warning) | Come il livello Tutti, tutti i messaggi, incluso il livello Trace, verranno registrati |
| [Trace](#Trace) | Il livello di registrazione per includere i messaggi dal livello Warning al livello Error |
| [All](#All) | Tutti gli eventi di livello Log (Error, Warning, Trace) saranno inclusi nella registrazione |
### None {#None}
```
public static final int None
```


Nessuna limitazione di logging, tutte le informazioni verranno registrate dalla traccia, avviso agli errori

### Error {#Error}
```
public static final int Error
```


Nessuna limitazione di logging, tutte le informazioni verranno registrate dalla traccia, avviso agli errori

### Warning {#Warning}
```
public static final int Warning
```


Come il livello Tutti, tutti i messaggi, incluso il livello Trace, verranno registrati

### Trace {#Trace}
```
public static final int Trace
```


Il livello di registrazione per includere i messaggi dal livello Warning al livello Error

### All {#All}
```
public static final int All
```


Tutti gli eventi di livello Log (Error, Warning, Trace) saranno inclusi nella registrazione

