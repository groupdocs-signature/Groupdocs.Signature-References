---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Παρέχει δεδομένα για το γεγονός ολοκλήρωσης της επαλήθευσης υπογραφής και των διαδικασιών αναζήτησης."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Παρέχει δεδομένα για το πλήρες γεγονός των διαδικασιών υπογραφής, επαλήθευσης και αναζήτησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCompleted()](#getCompleted--) | Αναπαριστά το χρονικό σημάδι ολοκλήρωσης της διαδικασίας. |
| [setCompleted(Date value)](#setCompleted-java.util.Date-) | Αναπαριστά το χρονικό σημάδι ολοκλήρωσης της διαδικασίας. |
| [getTicks()](#getTicks--) | Αναπαριστά τον χρόνο σε χιλιοστά του δευτερολέπτου που διατέθηκε από το γεγονός Έναρξη της διαδικασίας. |
| [setTicks(long value)](#setTicks-long-) | Αναπαριστά τον χρόνο σε χιλιοστά του δευτερολέπτου που διατέθηκε από το γεγονός Έναρξη της διαδικασίας. |
| [getTotalSignatures()](#getTotalSignatures--) | Αναπαριστά τη συνολική ποσότητα επεξεργασμένων υπογραφών. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | Αναπαριστά τη συνολική ποσότητα επεξεργασμένων υπογραφών. |
| [getCanceled()](#getCanceled--) | Δείχνει εάν η διαδικασία ακυρώθηκε. |
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Αναπαριστά το χρονικό σημάδι ολοκλήρωσης της διαδικασίας.

**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Αναπαριστά το χρονικό σημάδι ολοκλήρωσης της διαδικασίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Αναπαριστά τον χρόνο σε χιλιοστά του δευτερολέπτου που διατέθηκε από το γεγονός Έναρξη της διαδικασίας.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Αναπαριστά τον χρόνο σε χιλιοστά του δευτερολέπτου που διατέθηκε από το γεγονός Έναρξη της διαδικασίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Αναπαριστά τη συνολική ποσότητα επεξεργασμένων υπογραφών.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Αναπαριστά τη συνολική ποσότητα επεξεργασμένων υπογραφών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Δείχνει εάν η διαδικασία ακυρώθηκε.

**Returns:**
boolean
