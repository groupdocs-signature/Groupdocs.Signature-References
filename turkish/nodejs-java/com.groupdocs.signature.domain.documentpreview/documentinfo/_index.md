---
title: "DocumentInfo"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belge açıklama özelliklerini tanımlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Belge açıklama özelliklerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | Yeni bir [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageCount()](#getPageCount--) | Belge sayfa sayısı. |
| [setPageCount(int value)](#setPageCount-int-) | Belge sayfa sayısı. |
| [getPages()](#getPages--) | Belge sayfa açıklamalarının koleksiyonu. |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Belge sayfa açıklamalarının koleksiyonu. |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Maksimum sayfa yüksekliği için genişliği belirtir. |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Maksimum sayfa yüksekliği için genişliği belirtir. |
| [getMaxPageHeight()](#getMaxPageHeight--) | Maksimum sayfa yüksekliğini belirtir. |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Maksimum sayfa yüksekliğini belirtir. |
| [getFileType()](#getFileType--) | Dosya formatı türü. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Dosya formatı türü. |
| [getSize()](#getSize--) | Belge boyutu bayt cinsinden. |
| [setSize(long value)](#setSize-long-) | Belge boyutu bayt cinsinden. |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | Belge metin imzalarının koleksiyonu. |
| [getImageSignatures()](#getImageSignatures--) | [Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge görüntü imzalarının koleksiyonu. |
| [getDigitalSignatures()](#getDigitalSignatures--) | [Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge dijital imzalarının koleksiyonu. |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | [Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge barkod imzalarının koleksiyonu. |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | [Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge QR-kodu imzalarının koleksiyonu. |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | [Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge Form Alanı imzalarının koleksiyonu. |
| [getFormFields()](#getFormFields--) | Belgedeki mevcut tüm desteklenen Form Alanlarının koleksiyonu. |
| [getMetadataSignatures()](#getMetadataSignatures--) | Belge Meta Veri imzalarının koleksiyonu. |
| [getProcessLogs()](#getProcessLogs--) | İmzalama, Güncelleme, Silme gibi belge geçmişi işlemlerinin koleksiyonu. |
| [getSignatures()](#getSignatures--) | Belgenin tüm tip imzalarının koleksiyonu [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Yeni bir [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) sınıfının bir örneğini başlatır.

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Belge sayfa sayısı.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Belge sayfa sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Belge sayfa açıklamalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Belge sayfa açıklamalarının koleksiyonu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Maksimum sayfa yüksekliği için genişliği belirtir.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Maksimum sayfa yüksekliği için genişliği belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Maksimum sayfa yüksekliğini belirtir.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Maksimum sayfa yüksekliğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Dosya formatı türü.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Dosya formatı türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Belge boyutu bayt cinsinden.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Belge boyutu bayt cinsinden.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Belge metin imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


[Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge görüntü imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


[Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge dijital imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


[Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge barkod imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


[Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge QR-kodu imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


[Signature](../../com.groupdocs.signature/signature) yöntemleriyle eklenen veya güncellenen belge Form Alanı imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Belgedeki mevcut tüm desteklenen Form Alanlarının koleksiyonu. Bu özellik yalnızca Pdf ve Word İşleme belge türleri için desteklenir.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Belge Meta Veri imzalarının koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


İmzalama, Güncelleme, Silme gibi belge geçmişi işlemlerinin koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Belgenin tüm tip imzalarının koleksiyonu [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
