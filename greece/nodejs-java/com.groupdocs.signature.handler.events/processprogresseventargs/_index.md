---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Παρέχει δεδομένα για το συμβάν OnProgress των διαδικασιών επαλήθευσης υπογραφής και αναζήτησης."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Παρέχει δεδομένα για το γεγονός OnProgress των διαδικασιών υπογραφής, επαλήθευσης και αναζήτησης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getProgress()](#getProgress--) | Αναπαριστά την πρόοδο σε ποσοστά. |
| [setProgress(int value)](#setProgress-int-) | Αναπαριστά την πρόοδο σε ποσοστά. |
| [getTicks()](#getTicks--) | Αναπαριστά το χρόνο που δαπανήθηκε σε χιλιοστά του δευτερολέπτου από το συμβάν Start της διαδικασίας. |
| [setTicks(long value)](#setTicks-long-) | Αναπαριστά το χρόνο που δαπανήθηκε σε χιλιοστά του δευτερολέπτου από το συμβάν Start της διαδικασίας. |
| [getProcessedSignatures()](#getProcessedSignatures--) | Αναπαριστά την ποσότητα των επεξεργασμένων υπογραφών. |
| [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Αναπαριστά την ποσότητα των επεξεργασμένων υπογραφών. |
| [getCancel()](#getCancel--) | Δείχνει αν η διαδικασία πρέπει να ακυρωθεί. |
| [setCancel(boolean value)](#setCancel-boolean-) | Δείχνει αν η διαδικασία πρέπει να ακυρωθεί. |
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Αναπαριστά την πρόοδο σε ποσοστά. Το εύρος τιμών είναι από 0 έως 100.

**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Αναπαριστά την πρόοδο σε ποσοστά. Το εύρος τιμών είναι από 0 έως 100.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Αναπαριστά το χρόνο που δαπανήθηκε σε χιλιοστά του δευτερολέπτου από το συμβάν Start της διαδικασίας.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Αναπαριστά το χρόνο που δαπανήθηκε σε χιλιοστά του δευτερολέπτου από το συμβάν Start της διαδικασίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Αναπαριστά την ποσότητα των επεξεργασμένων υπογραφών.

**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Αναπαριστά την ποσότητα των επεξεργασμένων υπογραφών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Δείχνει αν η διαδικασία πρέπει να ακυρωθεί.

**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Δείχνει αν η διαδικασία πρέπει να ακυρωθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

