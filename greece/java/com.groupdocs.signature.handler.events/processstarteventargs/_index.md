---
title: "ProcessStartEventArgs"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Παρέχει δεδομένα για το συμβάν Start της διαδικασίας επαλήθευσης υπογραφής και αναζήτησης."
type: docs
weight: 15
url: /el/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Παρέχει δεδομένα για το γεγονός Start των διαδικασιών υπογραφής, επαλήθευσης και αναζήτησης

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getStarted()](#getStarted--) | Αντιπροσωπεύει το χρονικό σημείο έναρξης της διαδικασίας. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Αντιπροσωπεύει το χρονικό σημείο έναρξης της διαδικασίας. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Αντιπροσωπεύει τη συνολική ποσότητα των υπογραφών που θα υποβληθούν σε επεξεργασία. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Αντιπροσωπεύει τη συνολική ποσότητα των υπογραφών που θα υποβληθούν σε επεξεργασία. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Αντιπροσωπεύει το χρονικό σημείο έναρξης της διαδικασίας.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Αντιπροσωπεύει το χρονικό σημείο έναρξης της διαδικασίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Αντιπροσωπεύει τη συνολική ποσότητα των υπογραφών που θα υποβληθούν σε επεξεργασία.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Αντιπροσωπεύει τη συνολική ποσότητα των υπογραφών που θα υποβληθούν σε επεξεργασία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

