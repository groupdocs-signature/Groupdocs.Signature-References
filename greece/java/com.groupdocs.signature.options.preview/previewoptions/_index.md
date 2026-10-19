---
title: "PreviewOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά επιλογές προεπισκόπησης εγγράφου."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Αναπαριστά επιλογές προεπισκόπησης εγγράφου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Αρχικοποιεί το αντικείμενο PreviewOptions. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Αρχικοποιεί το αντικείμενο PreviewOptions. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Αρχικοποιεί το αντικείμενο PreviewOptions. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος των εικόνων προεπισκόπησης. |
|
|  | [setWidth(int value)](#setWidth-int-) | Λαμβάνει ή ορίζει το πλάτος των εικόνων προεπισκόπησης. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος των εικόνων προεπισκόπησης. |
|
|  | [setHeight(int value)](#setHeight-int-) | Λαμβάνει ή ορίζει το ύψος των εικόνων προεπισκόπησης. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Λαμβάνει ή ορίζει τους αριθμούς σελίδων των εικόνων προεπισκόπησης. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Λαμβάνει ή ορίζει τους αριθμούς σελίδων των εικόνων προεπισκόπησης. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Λαμβάνει ή ορίζει τη σημαία για απόκρυψη των υπογραφών από την εικόνα προεπισκόπησης σελίδας. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Λαμβάνει ή ορίζει τη σημαία για απόκρυψη των υπογραφών από την εικόνα προεπισκόπησης σελίδας. |
|
|  | [getResolution()](#getResolution--) | Λαμβάνει την ανάλυση των εικόνων προεπισκόπησης σε DPI (σημεία ανά ίντσα). |
|
|  | [setResolution(int value)](#setResolution-int-) | Ορίζει την ανάλυση των εικόνων προεπισκόπησης σε DPI (σημεία ανά ίντσα). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Αρχικοποιεί το αντικείμενο PreviewOptions.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Διεπαφή που ορίζει τη μέθοδο για τη δημιουργία ροής προεπισκόπησης σελίδας εξόδου. |
|
|  | pageNumbers | int[] | Επιθυμητοί αριθμοί σελίδων |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Αρχικοποιεί το αντικείμενο PreviewOptions.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Διεπαφή που ορίζει τη μέθοδο για τη δημιουργία ροής προεπισκόπησης σελίδας εξόδου. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Αρχικοποιεί το αντικείμενο PreviewOptions.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Διαδρομή προς το αρχείο εξόδου. |
|
|  | pageNumbers | int[] | Επιθυμητοί αριθμοί σελίδων |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει ή ορίζει το πλάτος των εικόνων προεπισκόπησης.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Λαμβάνει ή ορίζει το πλάτος των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει ή ορίζει το ύψος των εικόνων προεπισκόπησης.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Λαμβάνει ή ορίζει το ύψος των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Λαμβάνει ή ορίζει τους αριθμούς σελίδων των εικόνων προεπισκόπησης.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Λαμβάνει ή ορίζει τους αριθμούς σελίδων των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Λαμβάνει ή ορίζει τη σημαία για απόκρυψη των υπογραφών από την εικόνα προεπισκόπησης σελίδας.
Μόνο οι υπογραφές που έχουν σημειωθεί ως IsSignature θα κρύβονται από την εικόνα της σελίδας του παραγόμενου εγγράφου.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για απόκρυψη των υπογραφών από την εικόνα προεπισκόπησης σελίδας.
Μόνο οι υπογραφές που έχουν σημειωθεί ως IsSignature θα κρύβονται από την εικόνα της σελίδας του παραγόμενου εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Λαμβάνει την ανάλυση των εικόνων προεπισκόπησης σε DPI (σημεία ανά ίντσα).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Ορίζει την ανάλυση των εικόνων προεπισκόπησης σε DPI (σημεία ανά ίντσα).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

