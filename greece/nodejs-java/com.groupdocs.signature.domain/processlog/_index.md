---
title: "ProcessLog"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις λεπτομέρειες της διαδικασίας εγγράφου."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Αντιπροσωπεύει τις λεπτομέρειες της διαδικασίας εγγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDate()](#getDate--) | Λάβετε την ημερομηνία και ώρα της διαδικασίας. |
| [getType()](#getType--) | Λάβετε τον τύπο της διαδικασίας. |
| [getMessage()](#getMessage--) | Λάβετε την περιγραφή της διαδικασίας. |
| [getSucceeded()](#getSucceeded--) | Ποσότητα των υπογραφών που επεξεργάστηκαν επιτυχώς. |
| [getFailed()](#getFailed--) | Ποσότητα των υπογραφών που απέτυχαν κατά την επεξεργασία. |
| [getSignatures()](#getSignatures--) | Η λίστα των υπογραφών που επεξεργάστηκαν επιτυχώς. |
### getDate() {#getDate--}
```
public final Date getDate()
```


Λάβετε την ημερομηνία και ώρα της διαδικασίας.

**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Λάβετε τον τύπο της διαδικασίας.

**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Λάβετε την περιγραφή της διαδικασίας.

**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Ποσότητα των υπογραφών που επεξεργάστηκαν επιτυχώς.

**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Ποσότητα των υπογραφών που απέτυχαν κατά την επεξεργασία.

**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Η λίστα των υπογραφών που επεξεργάστηκαν επιτυχώς.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
