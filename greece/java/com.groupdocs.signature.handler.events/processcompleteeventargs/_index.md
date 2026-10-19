---
title: "ProcessCompleteEventArgs"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Παρέχει δεδομένα για το γεγονός ολοκλήρωσης της επαλήθευσης υπογραφής και των διαδικασιών αναζήτησης."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Παρέχει δεδομένα για το γεγονός ολοκλήρωσης των διαδικασιών υπογραφής, επαλήθευσης και αναζήτησης.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Αντιπροσωπεύει το χρονικό σημάδι ολοκλήρωσης της διεργασίας. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Αντιπροσωπεύει το χρονικό σημάδι ολοκλήρωσης της διεργασίας. |
|
|  | [getTicks()](#getTicks--) | Αντιπροσωπεύει το χρόνο σε χιλιοστά του δευτερολέπτου που έχει περάσει από το γεγονός Start. |
|
|  | [setTicks(long value)](#setTicks-long-) | Αντιπροσωπεύει το χρόνο σε χιλιοστά του δευτερολέπτου που έχει περάσει από το γεγονός Start. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Αντιπροσωπεύει τη συνολική ποσότητα επεξεργασμένων υπογραφών. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Αντιπροσωπεύει τη συνολική ποσότητα επεξεργασμένων υπογραφών. |
|
|  | [getCanceled()](#getCanceled--) | Δείχνει εάν η διεργασία ακυρώθηκε. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Αντιπροσωπεύει το χρονικό σημάδι ολοκλήρωσης της διεργασίας.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Αντιπροσωπεύει το χρονικό σημάδι ολοκλήρωσης της διεργασίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Αντιπροσωπεύει το χρόνο σε χιλιοστά του δευτερολέπτου που έχει περάσει από το γεγονός Start.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Αντιπροσωπεύει το χρόνο σε χιλιοστά του δευτερολέπτου που έχει περάσει από το γεγονός Start.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Αντιπροσωπεύει τη συνολική ποσότητα επεξεργασμένων υπογραφών.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Αντιπροσωπεύει τη συνολική ποσότητα επεξεργασμένων υπογραφών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Δείχνει εάν η διεργασία ακυρώθηκε.


**Returns:**
boolean
