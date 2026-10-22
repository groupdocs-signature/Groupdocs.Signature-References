---
title: "FileLogger"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Γράφει μηνύματα καταγραφής στο αρχείο."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Γράφει μηνύματα καταγραφής στο αρχείο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Δημιουργία καταγραφέα σε αρχείο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Γράφει ένα μήνυμα σφάλματος στην κονσόλα. |
| [trace(String message)](#trace-java.lang.String-) | Γράφει μήνυμα εντοπισμού στην κονσόλα. |
| [warning(String message)](#warning-java.lang.String-) | Γράφει μήνυμα προειδοποίησης στην κονσόλα· Τα μηνύματα προειδοποίησης παρέχουν πληροφορίες για το απρόσμενο και ανακτήσιμο γεγονός στη ροή της εφαρμογής. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Δημιουργία καταγραφέα σε αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Πλήρες όνομα αρχείου με διαδρομή |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Γράφει ένα μήνυμα σφάλματος στην κονσόλα. Τα μηνύματα σφάλματος παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα σφάλματος. |
| εξαίρεση | java.lang.Exception | Η εξαίρεση. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Γράφει μήνυμα εντοπισμού στην κονσόλα. Τα μηνύματα εντοπισμού παρέχουν γενικά χρήσιμες πληροφορίες για τη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα εντοπισμού. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Γράφει μήνυμα προειδοποίησης στην κονσόλα· Τα μηνύματα προειδοποίησης παρέχουν πληροφορίες για το απρόσμενο και ανακτήσιμο γεγονός στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα προειδοποίησης. |

