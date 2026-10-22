---
title: "DicomXmpEntry"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Καταχώρηση δεδομένων XMP για εικόνες DICOM .dcm."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

Καταχώρηση δεδομένων XMP για εικόνες DICOM (.dcm).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | Δημιουργεί καταχώρηση Xmp για εικόνα DICOM. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Τύπος καταχώρησης. |
| [getValue()](#getValue--) | Τιμή καταχώρησης. |
| [toString()](#toString--) | Λάβετε κειμενική αναπαράσταση της καταχώρησης Xmp. |
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


Δημιουργεί καταχώρηση Xmp για εικόνα DICOM.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Τύπος καταχώρησης |
| τιμή | java.lang.String | Τιμή καταχώρησης |

### getType() {#getType--}
```
public final int getType()
```


Τύπος καταχώρησης.

**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


Τιμή καταχώρησης.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Λάβετε κειμενική αναπαράσταση της καταχώρησης Xmp.

**Returns:**
java.lang.String - Κειμενική αναπαράσταση της καταχώρησης Xmp.
