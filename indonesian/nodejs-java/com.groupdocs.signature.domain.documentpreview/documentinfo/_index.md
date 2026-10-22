---
title: "DocumentInfo"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mendefinisikan properti deskripsi dokumen."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Mendefinisikan properti deskripsi dokumen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | Menginisialisasi sebuah instance baru dari kelas [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageCount()](#getPageCount--) | Jumlah halaman dokumen. |
| [setPageCount(int value)](#setPageCount-int-) | Jumlah halaman dokumen. |
| [getPages()](#getPages--) | Koleksi deskripsi halaman dokumen. |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Koleksi deskripsi halaman dokumen. |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Menentukan lebar untuk tinggi halaman maksimum. |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Menentukan lebar untuk tinggi halaman maksimum. |
| [getMaxPageHeight()](#getMaxPageHeight--) | Menentukan tinggi halaman maksimum. |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Menentukan tinggi halaman maksimum. |
| [getFileType()](#getFileType--) | Tipe format file. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Tipe format file. |
| [getSize()](#getSize--) | Ukuran dokumen dalam byte. |
| [setSize(long value)](#setSize-long-) | Ukuran dokumen dalam byte. |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | Koleksi tanda tangan teks dokumen. |
| [getImageSignatures()](#getImageSignatures--) | Koleksi tanda tangan gambar dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature). |
| [getDigitalSignatures()](#getDigitalSignatures--) | Koleksi tanda tangan digital dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature). |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | Koleksi tanda tangan barcode dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature). |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | Koleksi tanda tangan kode QR dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature). |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | Koleksi tanda tangan Form Field dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature). |
| [getFormFields()](#getFormFields--) | Koleksi semua Form Field yang didukung dan ada dalam dokumen. |
| [getMetadataSignatures()](#getMetadataSignatures--) | Koleksi tanda tangan Metadata dokumen. |
| [getProcessLogs()](#getProcessLogs--) | Koleksi proses riwayat dokumen seperti Sign, Update, Delete. |
| [getSignatures()](#getSignatures--) | Koleksi semua tipe tanda tangan dokumen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Menginisialisasi sebuah instance baru dari kelas [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Jumlah halaman dokumen.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Jumlah halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Koleksi deskripsi halaman dokumen.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Koleksi deskripsi halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Menentukan lebar untuk tinggi halaman maksimum.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Menentukan lebar untuk tinggi halaman maksimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Menentukan tinggi halaman maksimum.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Menentukan tinggi halaman maksimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Tipe format file.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Tipe format file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Ukuran dokumen dalam byte.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Ukuran dokumen dalam byte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Koleksi tanda tangan teks dokumen.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Koleksi tanda tangan gambar dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Koleksi tanda tangan digital dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Koleksi tanda tangan barcode dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Koleksi tanda tangan kode QR dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Koleksi tanda tangan Form Field dokumen yang ditambahkan atau diperbarui oleh metode [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Koleksi semua Form Field yang didukung yang ada dalam dokumen. Properti ini hanya didukung untuk tipe dokumen Pdf dan Word Processing.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Koleksi tanda tangan Metadata dokumen.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Koleksi proses riwayat dokumen seperti Sign, Update, Delete.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Koleksi semua tipe tanda tangan dokumen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
