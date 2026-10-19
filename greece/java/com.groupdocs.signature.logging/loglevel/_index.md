---
title: "LogLevel"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Καθορίζει τους διαθέσιμους τύπους επιπέδων καταγραφής."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Καθορίζει τους διαθέσιμους τύπους επιπέδων καταγραφής.
Αυτή η απαρίθμηση μπορεί να χρησιμοποιηθεί ως σημαίες για να ορίσει πολλές πιθανές τιμές ως ενεργοποιημένα bits
Παράδειγμα: LogLevel.Error \| LogLevel.Warning or LogLevel.Error \| LogLevel.Trace

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [None](#None) | Καμία περιορισμένη καταγραφή, όλες οι πληροφορίες θα καταγραφούν από το trace, την προειδοποίηση έως τα σφάλματα |
|
|  | [Error](#Error) | Καμία περιορισμένη καταγραφή, όλες οι πληροφορίες θα καταγραφούν από το trace, την προειδοποίηση έως τα σφάλματα |
|
|  | [Warning](#Warning) | Ίδιο με το επίπεδο All, όλα τα μηνύματα συμπεριλαμβανομένου του επιπέδου Trace θα καταγραφούν |
|
|  | [Trace](#Trace) | Το επίπεδο καταγραφής για να περιλαμβάνει μηνύματα από το επίπεδο Προειδοποίησης έως το Σφάλμα |
|
|  | [All](#All) | Όλα τα γεγονότα επιπέδου Log (Error, Warning, Trace) θα συμπεριληφθούν στην καταγραφή |
|
### None {#None}
```
public static final int None
```


Καμία περιορισμένη καταγραφή, όλες οι πληροφορίες θα καταγραφούν από το trace, την προειδοποίηση έως τα σφάλματα


### Error {#Error}
```
public static final int Error
```


Καμία περιορισμένη καταγραφή, όλες οι πληροφορίες θα καταγραφούν από το trace, την προειδοποίηση έως τα σφάλματα


### Warning {#Warning}
```
public static final int Warning
```


Ίδιο με το επίπεδο All, όλα τα μηνύματα συμπεριλαμβανομένου του επιπέδου Trace θα καταγραφούν


### Trace {#Trace}
```
public static final int Trace
```


Το επίπεδο καταγραφής για να περιλαμβάνει μηνύματα από το επίπεδο Προειδοποίησης έως το Σφάλμα


### All {#All}
```
public static final int All
```


Όλα τα γεγονότα επιπέδου Log (Error, Warning, Trace) θα συμπεριληφθούν στην καταγραφή


