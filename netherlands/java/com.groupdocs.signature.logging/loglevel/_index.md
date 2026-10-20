---
title: "LogLevel"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Specificeert welke soorten berichten worden doorgegeven aan de logger die is ingesteld in SignatureSettings."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Specificeert welke soorten berichten worden doorgegeven aan de logger die is ingesteld in
SignatureSettings
.
De waarden zijn vlaggen en kunnen bijvoorbeeld worden gecombineerd
LogLevel.Error \| LogLevel.Warning
.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [None](#None) | Er wordt niets gelogd. |
|
|  | [Error](#Error) | Fouten: een bewerking is mislukt. |
|
|  | [Warning](#Warning) | Waarschuwingen: een bewerking is geslaagd, maar het resultaat is mogelijk niet wat u verwacht. |
|
|  | [Trace](#Trace) | Traces: de stappen van een bewerking, zoals het begin en het einde. |
|
|  | [All](#All) | Fouten, waarschuwingen en traces. |
|
### None {#None}
```
public static final int None
```


Er wordt niets gelogd.


### Error {#Error}
```
public static final int Error
```


Fouten: een bewerking is mislukt.


### Warning {#Warning}
```
public static final int Warning
```


Waarschuwingen: een bewerking is geslaagd, maar het resultaat is mogelijk niet wat u verwacht.


### Trace {#Trace}
```
public static final int Trace
```


Traces: de stappen van een bewerking, zoals het begin en het einde.


### All {#All}
```
public static final int All
```


Fouten, waarschuwingen en traces. Dit is de standaard.


