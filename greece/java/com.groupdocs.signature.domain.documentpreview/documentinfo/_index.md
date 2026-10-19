---
title: "DocumentInfo"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Ορίζει ιδιότητες περιγραφής εγγράφου."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Ορίζει ιδιότητες περιγραφής εγγράφου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | Αριθμός σελίδων εγγράφου. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Αριθμός σελίδων εγγράφου. |
|
|  | [getPages()](#getPages--) | Συλλογή περιγραφών σελίδων εγγράφου. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Συλλογή περιγραφών σελίδων εγγράφου. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Καθορίζει το πλάτος για το μέγιστο ύψος σελίδας. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Καθορίζει το πλάτος για το μέγιστο ύψος σελίδας. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | Καθορίζει το μέγιστο ύψος σελίδας. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Καθορίζει το μέγιστο ύψος σελίδας. |
|
|  | [getFileType()](#getFileType--) | Τύπος μορφής αρχείου. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Τύπος μορφής αρχείου. |
|
|  | [getSize()](#getSize--) | Μέγεθος εγγράφου σε bytes. |
|
|  | [setSize(long value)](#setSize-long-) | Μέγεθος εγγράφου σε bytes. |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | Συλλογή υπογραφών κειμένου εγγράφου. |
|
|  | [getImageSignatures()](#getImageSignatures--) | Συλλογή υπογραφών εικόνας εγγράφου που προστέθηκαν ή ενημερώθηκαν από μεθόδους [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | Συλλογή ψηφιακών υπογραφών εγγράφου που προστέθηκαν ή ενημερώθηκαν από μεθόδους [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | Συλλογή υπογραφών barcode εγγράφου που προστέθηκαν ή ενημερώθηκαν από τις μεθόδους [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | Συλλογή υπογραφών QR-code εγγράφου που προστέθηκαν ή ενημερώθηκαν από τις μεθόδους [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | Συλλογή υπογραφών Form Field εγγράφου που προστέθηκαν ή ενημερώθηκαν από τις μεθόδους [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFields()](#getFormFields--) | Συλλογή όλων των υπαρχουσών υποστηριζόμενων πεδίων Form Fields στο έγγραφο. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | Συλλογή υπογραφών Metadata εγγράφου. |
|
|  | [getProcessLogs()](#getProcessLogs--) | Συλλογή διαδικασιών ιστορικού εγγράφου όπως Υπογραφή, Ενημέρωση, Διαγραφή. |
|
|  | [getSignatures()](#getSignatures--) | Συλλογή όλων των τύπων υπογραφών εγγράφου [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Αριθμός σελίδων εγγράφου.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Αριθμός σελίδων εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Συλλογή περιγραφών σελίδων εγγράφου.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Συλλογή περιγραφών σελίδων εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Καθορίζει το πλάτος για το μέγιστο ύψος σελίδας.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Καθορίζει το πλάτος για το μέγιστο ύψος σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Καθορίζει το μέγιστο ύψος σελίδας.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Καθορίζει το μέγιστο ύψος σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Τύπος μορφής αρχείου.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Τύπος μορφής αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Μέγεθος εγγράφου σε bytes.


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Μέγεθος εγγράφου σε bytes.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


Συλλογή υπογραφών κειμένου εγγράφου.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Συλλογή υπογραφών εικόνας εγγράφου που προστέθηκαν ή ενημερώθηκαν από μεθόδους [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Συλλογή ψηφιακών υπογραφών εγγράφου που προστέθηκαν ή ενημερώθηκαν από μεθόδους [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Συλλογή υπογραφών barcode εγγράφου που προστέθηκαν ή ενημερώθηκαν από τις μεθόδους [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Συλλογή υπογραφών QR-code εγγράφου που προστέθηκαν ή ενημερώθηκαν από τις μεθόδους [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Συλλογή υπογραφών Form Field εγγράφου που προστέθηκαν ή ενημερώθηκαν από τις μεθόδους [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Συλλογή όλων των υπαρχουσών υποστηριζόμενων πεδίων Form Fields στο έγγραφο. Αυτή η ιδιότητα υποστηρίζεται μόνο για τύπους εγγράφων Pdf και Word Processing.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Συλλογή υπογραφών Metadata εγγράφου.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Συλλογή διαδικασιών ιστορικού εγγράφου όπως Υπογραφή, Ενημέρωση, Διαγραφή.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Συλλογή όλων των τύπων υπογραφών εγγράφου [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
